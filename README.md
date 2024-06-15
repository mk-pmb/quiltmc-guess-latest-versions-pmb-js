
<!--#echo json="package.json" key="name" underline="=" -->
quiltmc-guess-latest-versions-pmb
=================================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Try to determine the latest versions of various QuiltMC components.
<!--/#echo -->


Usage
-----

```bash
./qlvupd.sh
```

* Cleans outdated cached files.
* Download missing files.
* Guess latest versions of various QuiltMC components.
* Write the report to `tmp.report.json` ([Example](docs/example/report.json)).



Configuration
-------------

see [cfg.default.rc](cfg.default.rc).





<!--#toc stop="scan" -->



Known issues
------------

* Needs more/better tests and docs.




&nbsp;


License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->
