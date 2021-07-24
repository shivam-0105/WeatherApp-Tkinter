# WeatherApp-Tkinter

In this Weather App, we used API from [openweatherapp](https://home.openweathermap.org), from where you can signin and get API key and use it.

## Required packages and How to install: 
1. Tkinter:  Standard GUI library for python
    ```
    pip install tk
    ```
2. Matplotlib: Python Package for data visualization
    ```
     pip install matplotlib 
    ```
3. Requests - Module which allows to send HTTP requests using Python
    ```
    pip install requests
    ```
4. CSV Reader - The csv module's reader object allow us to write into the file
   - from csv import reader    -    Write the data into csv file using reader
    ```
    import csv  
    ```
5. PIL Image - The Image module allows us to load images from files.
   ```
    pip install Pillow 
    ```
6. JSON - It is used to parse the JSON string using json.loads() and results in a python dictionary.
   ```
    pip install simplejson
    ```
7. Datetime - This module supplies classes for manipulating dates and times
    ```
    from datetime import datetime
    ```
    
## Functionalities Used:

### 1.	Exception Handling:
    •	Invalid city name: requests.exceptions.HTTPError:
    •	Internet connection failure: requests.exceptions.ConnectionError:
    •	Time out error: requests.exceptions.Timeout as errt:
    •	Other exceptions: requests.exceptions.RequestException as err:
    
### 2.	Matplot Library:
    •	Current Weather parameters plotting
    •	7-Days forecasting of different parameters of Weather plotting

### 3.	CSV Reader/Writer:
    •	Data stored in CSV file from Internet (API)
    •	Data was converted from JSON format to .csv format
    •	Data reading from CSV file for plotting graphs

### 4.	TKinter GUI:
    •	Main window of interaction
    •	Textbox, buttons, labels and other features are used to make application more interactable
    •	Image feature is used for displaying symbols corresponding to weather conditions
    
## Features of our Project:
    1.	It is an interactive GUI which is very User-Friendly.
    2.	User can enter City’s name whose weather information they want see.
    3.	It checks whether city name is correct or not.
    4.	It also checks for internet connection or any timeout error.
    5.	The following are the data shown by the Application: -
            •	Day-Date
            •	Current Temperature
            •	Min/Max temperature
            •	Weather description.
            •	Corresponding Weather icon
            •	Humidity
            •	Windspeed
            •	UV-Index
            •	Pressure.
            •	4-Days forecast of:
                    o	Temperature
                    o	Weather description
                    o	Corresponding Weather icon.
    6.	The Data Analysis of weather shown by the Application:
            •	Graph of 7-Days current temperature, min/max temperature, humidity, pressure.
## Images
![img1](https://user-images.githubusercontent.com/70219870/126772868-b86f8e13-45e9-4394-890b-482bc67ba99e.png)
![img2](https://user-images.githubusercontent.com/70219870/126772891-bcc4682e-101b-4836-b3c2-7616c017428a.png)
![img3](https://user-images.githubusercontent.com/70219870/126772905-b7932ce7-eb8c-4f78-b174-28cde4bddd59.png)
![img4](https://user-images.githubusercontent.com/70219870/126772913-0be8736f-3124-42ab-b1dd-30321a0fb490.png)


## Contributors
1. [19BCE150 - Shivam Panchal](https://github.com/shivam-0105)
2. [19BCE147 - Smit Pambhar](https://github.com/spambhar)
3. [19BCE142 - Neelkumar Kunjadiya](https://github.com/Neel-Kunjadiya)


I hope you enjoy the app

In case of any queries, suggestion or anything, you can contact me : Mail Id : shivampanchal0105@gmail.com

Thank you spending you precious time. Have a nice day :)

