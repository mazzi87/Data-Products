---
title: "Documentation"
author: "Andrea Mazzanti"
date: "January 30, 2016"
output: html_document
---


Welcome to the "Let me find the best car for you" app. This app helps you choose a car for a trip, using the mtcars dataset in [R]. 

You need to inform the distance of your trip and the price of gasoline in your region, so that the app can calculate the Gasoline Expenditure for each car in the dataset. Then, you can enter the maximum amount of money you want to spend on gasoline, and the table shows only the cars that have Miles per Gallon (mpg) that can go below this value.

Moreover, you can input some caractheristcs of the cars that you desire, such as Cylinders, Displacement, Horse Power and Transmission. The table will show only the cars with the filters selected. You can also sort the table according to the variable you want.

Source code for ui.R and server.R files are available on the [GitHub](https://github.com/mazzi87/Data-Products).