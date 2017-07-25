# Wikidata Referencing

Visualizing information about references in Wikidata. You can find all the data that has been used for the carrying out of this research [here](https://www.dropbox.com/s/kfcke8erq2g1ouu/Dataset.zip?dl=0).

## Code
To run the code, use Jupyter Notebook to run `References Script.ipynb`.

## Data
The `Data` folder contains `csv` files with information about references on the respective language Wikipedia. 

* `<language-code>_used_domains.csv` contain the domains used in this language of Wikipedia as reference.
* `<language-code>_used_tld.csv` contain the top-level-domains used in this language Wikipedia as reference.
* `item_types_*.csv` contains the information about the types of items in Wikidata.

## Figures
The `Figures` folder contains the generated graphs. The `pdf` files are the graphs, and their respective TeX files include the LaTeX code that is required in order for them to be included in LaTeX documents.

## License
This project is licensed under the terms of the Apache 2.0 License.
