[![pages-build-deployment](https://github.com/tyson-swetnam/home/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/tyson-swetnam/home/actions/workflows/pages/pages-build-deployment)

# Personal Website

[tysonswetnam.com](https://tysonswetnam.com)

Built using [MkDocs](https://www.mkdocs.org/) with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 

# Build instructions

```{bash}
git clone https://github.com/tyson-swetnam/home

cd home

pip install -r requirements.txt

python3 -m mkdocs serve
```

## Building with Insiders

after the initial build follow up with

```{bash}
pip install git+https://${GH_TOKEN}@github.com/squidfunk/mkdocs-material-insiders.git
```

Disabled `mkdocs-jupyter` for now due to version lag.