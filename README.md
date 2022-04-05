# BiletixSearchRobotviaUiPath
UiPath Activities, UI Explorer, arguments, and dynamic selector methods were used in this project.

Getting information about the user, logging in and filterings are seperate from each other by sequences. All sequences were brought together in the "Main" sequence.

The robot goes to "Biletix.com" and logs in. Then, it makes the necessary filters in line with the information given in the project and writes the results it finds to the Excel file.

Firstly, the robot gets your information like your username and password to the login biletix.com which sells and distributes tickets for events and log in. Using website filtering tools, the robot filters some events. Istanbul concerts, Izmir concerts, and Ankara arts were filtering conditions in this case.

If the project folder does not contain the "Event" folder, it is created by the robot. According to the search results, the creation of subfolders in this folder is also done by the robot. For example, if a concert is searched, the search results are saved in the Excel file, and this Excel file was created in the "Concert" folder.

You can see Excel output of the robot below..

![Excel_1](https://user-images.githubusercontent.com/64749586/161837826-0547d68c-341a-48c6-a5a7-fd2bc2b91be6.JPG)
![Excel_2](https://user-images.githubusercontent.com/64749586/161837905-aa7e9cf8-2134-473b-86bf-31cce812ee27.JPG)
![Excel_3](https://user-images.githubusercontent.com/64749586/161838188-f40c76a3-2d35-40f1-a785-a82f57a0e47d.JPG)
