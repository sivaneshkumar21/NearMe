# Ex03 Places Around Me
## Date: 01.12.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
~~~
map.html

<!DOCTYPE html>
<html>
<head>
<title>Ambur Tourist Map</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Ambur Tourist Map</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>SIVANESH KUMAR N(25001283)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Temple" title="Temple" href="temple.html" coords="398,773,141,641" shape="rect">
    <area target="_blank" alt="Tourist Place" title="Tourist Place" href="tourist.html" coords="850,382,635,280" shape="rect">
    <area target="_blank" alt="Lake view point" title="Lake view point" href="lake.html" coords="1358,480,1570,556" shape="rect">
    <area target="_blank" alt="Home Town" title="Home Town" href="home.html" coords="1651,416,1480,314" shape="rect">
</map>
</center>
</body>
</html>

home.html

<html>
    <head>
    <title>Home Town</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
    <font color="red"><b>Ambur Tourist Map</b></font>    
    </h1>    
    <h3 align="center">
    <font color="blue"><b>Seekkusunai village</b></font>    
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5">
    Seekkusunai village is known for the French colonial-era villas lining its leafy streets. Eateries from quirky cafes to upscale courtyard restaurants serve French, Indian, and Franco-Tamil cuisine, while small crafts shops dot cobbled lanes. The beachfront promenade is popular for evening strolls. Religious sites include the Sri Aurobindo Ashram meditation center and the ornate Arulmigu Manakula 
    </font>    
    </p>    
    </body>
</html>

lake.html

<html>
    <head>
    <title>Lake</title>
    </head>
    <body bgcolor="purple">
    <h1 align="center">
    <font color="red"><b>Ambur Tourist Map</b></font>    
    </h1>    
    <h3 align="center">
    <font color="Green"><b>Ambur Nayakaneri lake</b></font>    
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5" color="Yellow">
    A lake is simply a body of water surrounded by land. Ponds are considered small lakes, while some seas are technically large lakes.
    </font>    
    </p>    
    </body>
</html>

temple.html

<html>
    <head>
    <title>Temple</title>
    </head>
    <body bgcolor="yellow">
    <h1 align="center">
    <font color="red"><b>Ambur Tourist Map</b></font>    
    </h1>    
    <h3 align="center">
    <font color="blue"><b>Sri Panchamuga</b></font>    
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5">
    A temple is a building or sacred place used for worship, prayer, and spiritual rituals in many religions, including Hinduism, Buddhism, and certain branches of Judaism. While Christians typically refer to their houses of worship as churches, temples serve a similar function in other faiths, providing a spiritual center for communities to practice their beliefs.      
    </font>    
    </p>    
    </body>
</html>

tourist.html

<html>
    <head>
    <title>Touirst Place</title>
    </head>
    <body bgcolor="blue">
    <h1 align="center">
    <font color="red"><b>Ambur Tourist Map</b></font>    
    </h1>    
    <h3 align="center">
    <font color="black"><b></b>Vinkateswar</b></font>    
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5">
   "Vinkateswar" is a location in the Ambur R.F. area of Tamil Nadu, India. It is described as a national forest area that is good for children. 
    </font>    
    </p>    
    </body>
</html>


~~~
## OUTPUT:
![alt text](<Screenshot 2025-12-01 214308.png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
