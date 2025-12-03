# Ex03 Places Around Me
## Date: 3.12.2025

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
```
map.html
<html>
    <head>
        <title>NearMe</title>
    </head>
    <body>
        <header>
            <h1 align="center">madurai</h1>
            <br>
            <h4 align="center">LAKSHITA RAI -25005431</h4>
        </header>
    <img src="Screenshot 2025-12-03 155918.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="gopuram cinemas" title="gopuram cinemas" href="cinema.html" coords="610,134,823,208" shape="rect">
    <area target="" alt="vishall mall" title="vishall mall" href="mall.html" coords="976,132,1069,102,1162,141,1092,210,1008,193" shape="poly">
    <area target="" alt="apollo speciality hospitals madurai" title="apollo speciality hospitals madurai" href="hospital.html" coords="1467,399,117" shape="circle">
    <area target="" alt="weshtern park" title="weshtern park" href="park.html" coords="330,568,489,638" shape="rect">
    <area target="" alt="P.Power hotel & Mutton stall" title="P.Power hotel & Mutton stall" href="hotel.html" coords="" shape="poly">
</map>

    </body>
</html>    
```
```
cinema.html
<html>
    <head>
        <title>Nearme</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="orange">Madurai</font>
        </h1>
        <h3 align="center">
            <font color="">gopuram cinemas</font>
        </h3>
        <hr size="3" color="orange">
        <p align="justify">
            <font face="Arial" size="5">
                Gopuram Cinemas in Madurai, located in Sellur, is a multiplex cinema known for its modern features like Dolby Atmos and laser projection, offering an enhanced audio-visual experience.
            </font>
        </p>
        </body>
    </body>
</html>
```
```
hospital.html
<html>
    <head>
        <title>Nearme</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"></font>
        </h1>
        <h3 align="center">
            <font color="">apollo speciality hospitals madurai</font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
            <font face="Arial" size="5">
            apollo hospital is india's first corporate hospital,founded in 1983 by Dr.prathap C.Reddy
            </font>    
        </p>
        </body>
    </body>
</html>
```
```
hotel.html
<html>
    <head>
        <title>Nearme</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="pink">Madurai</font>
        </h1>
        <h3 align="center">
            <font color="">P.Power hotel & Mutton stall</font>
        </h3>
        <hr size="3" color="orange">
        <p align="justify">
            <font face="Arial" size="5">
                 "P.Power Hotel, also known as Power Kadai, is a popular, no-frills eatery in Madurai famous for its mutton and curry combination dishes, especially its mutton-based curries. Located on Market Road, near Navalar Nagar, it's a well-known local spot for authentic and flavorful non-vegetarian food."
            </font>
        </p>
        </body>
    </body>
</html>
```
```
mall.html
<html>
    <head>
        <title>Nearme</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="pink">Madurai</font>
        </h1>
        <h3 align="center">
            <font color="">vishall mall</font>
        </h3>
        <hr size="3" color="purple">
        <p align="justify">
            <font face="Arial" size="5">
              Vishaal De Mal is a popular mixed-use mall in Madurai that offers a variety of shopping, dining, and entertainment options
            </font>
        </p>
        </body>
    </body>
</html>
```
```
park.html
<html>
    <head>
        <title>Nearme</title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">
            <font color="rose">Madurai</font>
        </h1>
        <h3 align="center">
            <font color="">weshtern park</font>
        </h3>
        <hr size="3" color="peach">
        <p align="justify">
            <font face="Arial" size="5">
                "Weshtern Park" in Madurai refers to the Hotel Weshtern Park, a 3-star hotel located near the Madurai Railway Station. It offers a range of amenities including air-conditioned rooms, a swimming pool, a spa, and dining options. The hotel also provides services such as travel assistance, laundry, and free Wi-Fi.
            </font>
        </p>
        </body>
    </body>
</html>
```



## OUTPUT
![alt text](<Screenshot 2025-12-03 155918.png>)
![alt text](<Screenshot 2025-12-03 185842-2.png>)
![alt text](<Screenshot 2025-12-03 185156-1.png>)
![alt text](<Screenshot 2025-12-03 185344-1.png>)
![alt text](<Screenshot 2025-12-03 185116-1.png>)
![alt text](<Screenshot 2025-12-03 185135-1.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
