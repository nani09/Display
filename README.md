

work Flow

1) Created a response.json file assuming the response from server.
2)In service folder created a service GetImagesService to get data from response.json.
3)There are six components
    =>Home
    =>prescriptions
    =>mris
    =>usgs
    =>xrays
    =>bloodreports
    =>display
4)I have filtered the response and seperated all the images acording to their type.
5)I have created route as shown in app-routing.module to navigate.
6)Home component I have shown all types of images.
7)By clicking on the particular type we navigate there and displayed particular images, its properties and their form to digitalize the image.
8)To digitize we need to click button "Digitize Prescription", it shows up the for to fil.
9)If any form is partially updated before, it shows up the information.
10)By clicking on Home on nav bar it redirects to home page.
11)I have created only two type of forms, one is for prescriptions and other is for blood reports.
