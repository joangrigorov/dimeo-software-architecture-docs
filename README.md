# DiMeo Waste Management System Software Architecture Documentation

This is the repository containing the software architecture documentation sources of DiMeo Waste Management System.
Documentation is maintained by DiMeo R{AUTHOR}D Team.

## Building the documentation

### HTML version (with autobuild)
To build the documentation in an HTML variant run:

```shell
./sphinx autobuild
```

The documentation will run via a webserver on port 8000. A web browser window will open.

### PDF version
To build a PDF version you can run:

```shell
./sphinx
```

The output PDF file can be found in `build/latex` path.
