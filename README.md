# Customer-Segmentation-for-Indian-Bank

The data consists of transactional, demographic, and geographical information for bank customers in an Indian bank.

In a high level, the project consists of the following steps:

1. Exploratory data analyses to uncover customer behavior and demographic trends. <br>
2. Features were created to enrich segmentation analysis. <br>
3. Data was cleaned and prepared for the KMeans clustering model. <br>
4. Hyperparameter tuning to identify optimal number of clusters. <br>
5. Post hoc analysis to identify cluster specific marketing as well as customer acquisition recommendations.

# Setup

The "Customer Segmentation Project.ipynb" file was initially run in Python 3.8.8. However, Python 3.8 is already obsolete when I checked on April 9, 2025. So we will use Python 3.10. ```setup.sh``` downloads the necessary Python packages, gets a virtual environment set up, gets the csv file necessary for this project, and runs the jupyter notebook. ```requirements.txt``` consists all the Python packages that are needed in this project. The instructions are provided below.

1. Use a linux Ubuntu environment <br>
2. Run
```bash
chmod +x setup.sh
./setup.sh
```
3. In the terminal, click on the link provided. You will see the Jupyter notebook UI in port 8888. <br>

You should now be able to run the jupyter notebook and the ```Customer Segmentation Project.ipynb``` file.
