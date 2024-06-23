# Kickstarter-Projects-NN
Main goal is to train a model that will be able to predict whether a Kickstarter project will be successfull or not.

The database contains information about projects launched on the popular Kickstarter platform and their success. Kickstarter allows creators to present their projects to the public, seeking funding to bring their ideas to life. Data are collected from Kickstarter Platform.

Key Attributes:

ID: Project ID;
name: Project name;
category: Sub-category;
main_category: Main category of campaign;
currency: Currency used to support;
deadline: The date by which the project must reach its funding goal;
goal: The funding goal is the amount of money that a creator needs to complete their project;
launched: The date and time when the project was launched;
pledged: The amount pledged by "crowd";
state: The current status of the project (e.g., successful, failed, canceled, live, suspended);
backers: The number of backers who have pledged money to the project;
country: The country from which the project was launched;
usd_pledged: The amount of money pledged in US dollars, which is standardized to facilitate comparison across projects using different currencies;
usd_pledged_real;
usd_goal_real: The funding goal in US dollars, standardized for the same reason as USD Pledged;

Dataset: https://www.kaggle.com/datasets/kemical/kickstarter-projects

Main goal is to train a model that will be able to predict whether a Kickstarter project will be successfull or not. We will use a Neural Network to make our predictions.
The secondary goal is to explore the data, clean it and do a basic EDA analysis.
