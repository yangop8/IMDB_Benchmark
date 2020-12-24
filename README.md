# IMDB_Benchmark

This repository contains two main features. First, it can help convert from tsv files to an rdf file, which can be used by graph databases. Second, it transfer the [JOB](https://github.com/gregrahn/join-order-benchmark) (Join Order Benchmark) from SQL to [SPARQL](https://www.w3.org/TR/rdf-sparql-query/).

## Usage

* Download the IMDB datasets from https://datasets.imdbws.com/. Put them in the `raw_data` folder.
* Run the python script: 

  `python *.py`
* Load the rdf file `*.nt` into a graph database.
* Run queries in the `benchmark` folder.

## Questions

Contact Lei Yang (yangop8@pku.edu.cn) if you have any questions.

## Licensing

IMDB_Benchmark is open source under the Apache 2.0 license.