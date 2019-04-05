## Titanic 


### Importing Data (Titanic)

First we will need to import data. 

Select what type of data. In this case its Microsoft Excel(xls)

![sheet 1](img/pronto/pronto-connect.png "sheet1")


Navigate to where you saved the data and open the titanic file

![sheet 1](img/titanic/titanicfile.png "sheet1")



#### Explore your data (Pronto)

Know your data! Just like before, lets look at our data before going into visualizing our data.

![sheet 1](img/pronto/knowdata.png "sheet1")

### EmbarkMap

Click on `sheet 1` to go to our workplace

![sheet 1](img/fremont/sheet1.png "sheet1")

This time we're going to use multiple sheets, so lets rename our `sheet1 `. We're going to call it `EmbarkMap`.


![sheet 1](img/titanic/renamesheet.png "sheet1")


For this sheet we want to make a map!!!

Lets move Lets move `latitude` and `longitude` into dimensions. If we don't put them in dimensions it should actually still work in this example, but tableau will be trying to do a calculation on them. `AVG(latitude)`.


Lets populate our map!

- Drag `Longitude` into the columns sections

- Drag `Latitude` into the Rows Sections 


![sheet 1](img/titanic/loglat.png "sheet1")


Cool we have a map!!! Lets add in the Country and city displayed on the map.

- Drag `Country` into the marks section

- Drag `City` into the marks section

- Click the dots to the left of them and select `label`

![sheet 1](img/titanic/label.png "sheet1")


Our map should now show dots at the embarking point and the label of the country and city! We're done with it for now!


![sheet 1](img/titanic/finishmap.png "sheet1")

### EmbarkCount

Lets make a new sheet

![sheet 1](img/titanic/newsheet.png "sheet1")


And name it `EmbarkCount`. We want to get the number of people who left at each city. 

- Drag `City` to Columns
- Drag `Number of Records` to Rows(make sure is is SUM).


![sheet 1](img/titanic/emcount.png "sheet1")




This gives us the count, but lets get even more data!

- Drag `Pclass` into dimensions
- Drag `Pclass` into color marks 

![sheet 1](img/titanic/pclass.png "sheet1")

This is a cool break down showing the amount leaving from each city and how people were in first, second, and third class!


### Deaths

Make a new sheet and call it `Deaths`

- Drag `Pclass` into columns
- Drag `Dead or Alive`	into columns
- Drag `Number of Records` to Rows(make sure is is SUM).
- Drag `Pclass` into color marks

That was fast!

I hope you're beginning to see how fast tableau can be!

![sheet 1](img/titanic/deaths.png "sheet1")

### Dashboard

Dashboards are a place we can combine multiple sheets and charts in one place to tell a larger story!


Create a new dashboard. 

![sheet 1](img/titanic/dash.png "sheet1")

Lets call it `FullStory`


from the listed sheets Drag in `Embarkment` and `EmbarkCount`.

![sheet 1](img/titanic/dashsheets.png "sheet1")


It looks a little squished. Lets adjust the size of our dashboard.

![sheet 1](img/titanic/size.png "sheet1")

Lets put `1000` for now.


Drag in the remaining sheet


![sheet 1](img/titanic/fullstory.png "sheet1")


Toggle on highlighting selection


![sheet 1](img/titanic/toggle.png "sheet1")

### Lets make a story! 

