# INFO-I590-On-ramp-PySpark-NCAA
On-ramp assignment for utilizing the Apache data analytics stack for simple analysis of 2016 NCAA basketball data

## Background
The Hortonworks Sandbox is a personal, portable Hadoop environment (packaged as a virtual machine) that provides out-of-the-box access to the latest Apache-based data science toolsets. This includes Hadoop, Spark, and Zeppelin.

## Assigment
In this assignment, you will start up your own instance of the Hortonworks Sandbox VM to do simple analysis on NCAA basketball data for the current 2016 season. You will utilize a Zeppelin notebook to run analysis using Spark, a cluster computing framework similar to Hadoop except that it utilizes RDDs (in-memory datasets) to facilitate iterative algorithms and interactive/exploratory data analysis.

## Data
The data that will be used in this assignment comes from https://www.spreadsheet-sports.com/2015-ncaa-basketball-game-data. The link at the bottom of this page links to a dropbox location containing an excel doc of the 2016 game results for all NCAA men's basketball games up through 2016/03/01. To simplify parsing the data into RDDs for Spark, I opened up the excel sheet in MS Excel and saved the document as a CSV. This CSV is what is contained in this repo as `2016_NCAA_Game_Results_Data.csv`.

## Instructions
1. Install VirtualBox (https://www.virtualbox.org/wiki/Downloads).
2. Download the Hortonworks Sandbox (http://hortonworks.com/products/hortonworks-sandbox/#install). If you do not want to register, I've uploaded the VM to my IU google drive ().
3. Import the VM according to the instructions in `Import_on_Vbox_3_1_2016.pdf`. Information such as installed software, account login information, etc. are contained in the release notes `ReleaseNotes_3_3_2016.pdf`.
4. Once the instance is up and running, go through the "Hands-on Tour of Apache Spark in 5 Minutes" tutorial, `Spark_Tutorial.pdf` to quickly familiarize yourself with Zeppelin notebooks (similar to ipython/jupyter notebook in the first on-ramp) and Spark using PySpark (python binding to the Spark programming model).
5. Finally, load the Zeppelin notebook contained in this repo and complete the assignment.
