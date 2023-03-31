# Crowdfunding_ETL _(Project 2)_

This repository contains a mini team project in which we worked together to build an ETL pipeline using Python, Pandas, Python dictionary methods, and JSONs to extract and transform the data.

# Authors

- Jorge Alonso Lozano Tena [@loncho95](https://www.github.com/loncho95)
- César Augusto Cruz Reyes [@Csarcruz](https://www.github.com/Csarcruz)
- Jorge Alonso Lozano Tena [@daniel-r-murillo-antuna](https://www.github.com/daniel-r-murillo-antuna)

# Repository description:

The project included the extraction of data from two raw Excel files, which contained data from Crowdfunding pledges that resulted in different outcomes and belonged to different categories and subcategories. Then, we transformed the data to make them useful and exported four CSV files, which contained the Crowdfunding contacts, the campaigns information, the specific categories, and the specific subcategories to which each campaign belonged. Last, we created a SQL database and loaded the CSVs onto the database.

Our repository contains the following:

## A _Resources_ folder:

It has:
- The two raw Excel files, which we used for our ETL pipeline.
- The four CSV files that we exported and which contain the transformed data.

## The _crowdfunding_db_examples_ Folder:

It has four screenshots of how the SQL database works.

## The _ETL_Mini_Project_JLozano_CCruz_DMurillo_ Jupyter Notebook:

It contains the code we used to extract and transform the data and a preview of the CSV files that were created.

## A _Physical_ERD_ image:

It depicts a detailed relationship between the four entities created —from the four CSVs with transformed data—, their data types, primary keys, and foreign keys. It was modelled with the Quick Database Diagrams ([QuickDBD](https://www.quickdatabasediagrams.com/)) app.

## A _crowdfunding_db_schema_ SQL file:

It contains the table schema we created to load the transformed data of the four CSVs. Ww used PGAdmin4 to import the data into the SQL database we created:

As you can see in the following image, the transformed data was imported to the Campaign entity:
![image](https://github.com/loncho95/Crowdfunding_ETL/blob/main/crowdfunding_db_examples/campaign.png)

As you can see in the following image, the transformed data was imported to the Category entity:
![image](https://github.com/loncho95/Crowdfunding_ETL/blob/main/crowdfunding_db_examples/category.png)

As you can see in the following image, the transformed data was imported to the Contacts entity:
![image](https://github.com/loncho95/Crowdfunding_ETL/blob/main/crowdfunding_db_examples/contacts.png)

As you can see in the following image, the transformed data was imported to the Subcategory entity:
![image](https://github.com/loncho95/Crowdfunding_ETL/blob/main/crowdfunding_db_examples/subcategory.png)

```#Thank you for reading me!```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
