# Proof of concept using Formly JSON Schema along with Benchmarking Data Model 2.0

This proof of concept dynamically loads the different benchmarking data model schemas, in order to play with ()Angular Formly](https://formly.dev/). As these JSON Schemas heavily use [`$ref`](https://json-schema.org/understanding-json-schema/structuring.html#ref), and Formly JSON Schema does not support complex mappings of URIs to external JSON Schemas, this proof of concept also uses [json-schema-ref-parser](https://www.npmjs.com/package/json-schema-ref-parser).

Fragments from this code are inspired in several examples spread over internet.

## Installation instructions

* Install new enough NodeJS and npm. Tested with NodeJS v14.17.3 and npm 6.14.13 .

* Clone this repo and change to its directory.

* Run from the directory:

  ```bash
  npm install
  ```
  
  in order to install all the needed dependencies.

* Run from the same directory:

  ```bash
  npm run start
  ```
  
  in order to build the project and start the ng dev server at port 4200.
  
* Run from the same directory:

  ```bash
  npm run build
  ```
  
  in order to only build the project, which will be available at `dist/benchmarking_data_model_angular_test/`.
