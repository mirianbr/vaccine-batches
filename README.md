# Brazil vaccine-batches dataset

Project aimed at creating a public dataset for the COVID-19 vaccine batches sent to each of Brazil States by the Federal Government, between January to May 2021. 

The vaccine batches information is made available by the Brazilian government agency SAGE in PDF files, one file for each vaccine distribution phase. The PDF files are for [transport (freight) invoices](https://en.wikipedia.org/wiki/Transport_document), and they contain information about each vaccine batch (including its number and expiration dates). The picture below presents an example of such document.

![Transportation invoice example](https://raw.githubusercontent.com/mirianbr/vaccine-batches/main/assets/OK-ac_fase1-quality-dpi-depth-bg.png)

The data extraction was originally done using python, imagemagick and pytesseract (see [Jupyter Notebook](https://github.com/mirianbr/vaccine-batches/blob/main/vaccine-batches-dataset.ipynb)). You can see the raw result [here](https://github.com/mirianbr/vaccine-batches/blob/main/csv/batches-raw.csv).

The following partial clean sets are available:
* [For states Acre-AC, Alagoas-AL, Amazonas-AM only](https://github.com/mirianbr/vaccine-batches/blob/main/csv/batches-AC%2C%20AL%2C%20AM.csv)
* [For the Federal District](https://github.com/mirianbr/vaccine-batches/blob/main/csv/batches-DF.csv)
* [For the South region states - Paraná-PR, Rio Grande do Sul-RS, Santa Catarina-SC only](https://github.com/mirianbr/vaccine-batches/blob/main/csv/batches-PR%2C%20RS%2C%20SC.csv)

Current status (as of Aug 8th, 2021): cleaning the dataset to make it public. Feel free to contact me if you have any thoughts, suggestions or questions.

Original data source: https://sage.saude.gov.br/sistemas/vacina/vacina_fases.php
