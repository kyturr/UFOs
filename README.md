# UFOs

## Overview of Project

The purpose of this project is to create a webpage in which users can read about UFO sightings and then display data collected in January of 2010. This webpage is also responsive to user input and can filter the data by city, state, country, and/or shape. In addition, this project demonstrates proficiency in using javascript in tandem  with HTML to create webpages using functions, tables, libraries, and active response fields.

## Results

After loading the web page, a user can look through the various UFO sightings that will automatically display on to the bottom right columns of the web page. In order to filter the data, there are the 4 listed search criteria that can be used. Whenever the fields are empty they will display all data and the fields will be prepopulated by default values.

![image](https://user-images.githubusercontent.com/103979048/184060604-9bb59bf3-1eba-4b35-9f65-04287f04966d.png)


The user can input text in to any field and as soon as they press enter or click off of the field it will begin to filter. "ca" has been entered in state as an example below

![image](https://user-images.githubusercontent.com/103979048/184060733-d5d9e5e1-c65e-4ac9-a9d8-9456e6a41e02.png)


The table results is case sensitive. All fields should be completely lower case. Notice in the example below "CA" returns no results. All invalind searches will return no results.

![image](https://user-images.githubusercontent.com/103979048/184060874-11d43ca8-6cbf-480c-a3bc-cbdd0e7d6b0b.png)

Users can filter using multiple search criteria as well. Notice in the example below "ca" has been entered in to state and "light" has been entered in to shape.

![image](https://user-images.githubusercontent.com/103979048/184061098-83c318c9-a4c3-4129-82ce-d106d4e7319f.png)

Users can use up to all four criteria if they desire. Notice in the example, "el cajon" has been added as a city.

![image](https://user-images.githubusercontent.com/103979048/184061293-4e8d43b5-5361-48db-a29e-b847600881fb.png)


To remove filters, just delete the text that was input and press enter or click off the field. Notice in the example the shape "light" has been removed.

![image](https://user-images.githubusercontent.com/103979048/184061503-55b8215a-3ca1-4e84-95ae-12b57a436851.png)

Removing all fields will return the table to showing all results, ready to filter whichever criteria the user can think of next.

## Summary

The webpage is fully interactable and can help users find whichever information they need, though it does have it's faults. Fully relying on the user to be able to input the criteria perfectly spelled may not work for every user. For further development, the searching menu can have a dynamic dropdown that shows suggested auto-fill values based on what is being typed in. This will ensure that each search will yield results. The user should also be informed that all searches should be lower case, or searches should automatically reformat the searches to be lowercase. An additional problem with this webpage is that having large amounts of results on the table can be overwhelming. Thus, it would be beneficial to add a pages function that will display 5-10 results per page and on the table.
