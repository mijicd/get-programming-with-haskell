# Working with binary data 

The MARC (MAchine-Readable Cataloging) record is the standard format used for
representing bibliographic data. More details about it can be found at the
[following address][1].

Before proceeding, make sure to download the test data by executing following
command:

```bash
wget https://archive.org/download/marc_oregon_summit_records/catalog_files/ohsu_ncnm_wscc_bibs.mrc -O sample.mrc
```

## Summary

This chapter illustrates the techniques for handling binary data. More
specifically, it addresses the following:

- modeling textual data using `Text`
- processing binary data represented by `ByteString`
- transforming Unicode contents using `decodeUtf8` and `encodeUtf8`
- isolating effects via `IO`

[1]: https://www.loc.gov/marc/umb/um01to06.html
