# mkdocs-material-starter

mkdocs-material-starter

## Installation

With `virtualenv`:

```bash
$ virtualenv -p python3 venv
$ source ./venv/bin/activate
$ pip install -r requirements.txt
```

## Commands

* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.

## Deploy to S3

To deploy to AWS S3:

```bash
$ mkdocs build
$ aws s3 sync ./site s3://<your-bucket-name> --acl public-read
```

## More information

For more information please see the [index.md file](docs/index.md) inside
the `docs` folder.
