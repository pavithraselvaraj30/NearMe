# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>My Area</title>
    </head>
    <body>
        <h1 align="center">
            <font color="pink"><b>VELLORE</b></font> 
         </h1>
         <h3 align="center">
            <font color="blue"><b>Pavithra S (212223230147)</b></font>
         </h3>
         <center>
            <img src="map.png.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="Fortune Park" title="Fortune Park" href="Park.html" coords="603,35,732,79" shape="rect">
                <area target="" alt="Palamathi Hills" title="Palamathi Hills" href="Hills.html" coords="911,518,77" shape="circle">
                <area target="" alt="Vellore Fort" title="Vellore Fort" href="Fort.html" coords="618,258,824,308" shape="rect">
                <area target="" alt="G S Mahal" title="G S Mahal" href="Palace.html" coords="450,277,81" shape="circle">
                <area target="" alt="SMS Grand hotel" title="SMS Grand hotel" href="Hotel.html" coords="832,159,994,207" shape="rect">
            </map>

         </center>
        
        </body>
    
</html>

Park.html

<html>
    <head>
        <title>My Area</title>
    </head>
    <body bgcolor="sky blue">
        <h1 align="center">
            <font color="light red"><b>VELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="gold"><b>Fortune Park</b></font>
        </h3>
        <hr size="3" color="dark pink">
        <p align="justify">
            <font face="Georgia" size="5"></font>
            Centrally located, in Gandhi Nagar, Fortune Park is a full service hotel in Vellore offering premium accommodation with high-speed Wi-Fi connectivity, a choice of dining options, banqueting facilities, a fully-equipped gymnasium, swimming pool and spa more, for a comfortable stay in the city.
            </p>
         </body>
     </html>

Hills.html

<html>
    <head>
        <title>My Area</title>
    </head>
    <body bgcolor="violet">
        <h1 align="center">
            <font color="rose"><b>VELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="grey"><b>Palamathi Hills</b></font>
        </h3>
        <hr size="3" color="light green">
        <p align="justify">
            <font face="Georgia" size="5"></font>
            The Palamathi Hills are an extension of the Eastern Ghats spread across southeastern parts of Vellore City in Tamil Nadu. The Palamathi Hill range, the nearby Palamathi Reserve Forest, the Otteri lake is collectively referred to as Palamathi Hills. The area is a thriving hotspot for various birds and various flora.
            </p>
        </body>
     </html>

 Fort.html

<html>
    <head>
        <title>My Area</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="yellow"><b>VELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="dark blue"><b>Vellore Fort</b></font>
        </h3>
        <hr size="3" color="merun">
        <p align="justify">
            <font face="Georgia" size="5"></font>
            Vellore Fort is a large 16th-century fort in the center of Vellore city, in the state of Tamil Nadu, India. It was built by Vijayanagara kings. The fort was at one time the headquarters of the Aravidu Dynasty of the Vijayanagara Empire.
            </p>
         </body>
      </html>

Palace.html

<html>
    <head>
        <title>My Area</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="sky blue"><b>VELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="olive green"><b>G S Mahal</b></font>
        </h3>
        <hr size="3" color="white">
        <p align="justify">
            <font face="Georgia" size="5"></font>
            G S Mahal provides dedicated spaces for different ceremonies and rituals associated with weddings. This includes a stage for the couple, areas for religious ceremonies, and spaces for post-wedding celebrations. They offer flexibility in decor options.
            </p>
        </body>
</html>

Hotel.html

html>
    <head>
        <title>My Area</title>
    </head>
    <body bgcolor="silver">
        <h1 align="center">
            <font color="red"><b>VELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="purple"><b>SMS Grand hotel</b></font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
            <font face="Georgia" size="5"></font>
            SMS Grand Inn is the latest boutique addition to the Vellore Hospitality spectrum. This buzzing trading and industrial city is also home to the famed CMC hospital and medical college.A visit to the world renowned Golden temple at Sripuram just 12 Kms would complete your pleasant stay.
        </p>

        
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-03-26 144207.png>)
![alt text](<Screenshot 2024-03-27 194345.png>)
![alt text](<Screenshot 2024-03-27 194830.png>)
![alt text](<Screenshot 2024-03-27 195706.png>)
![alt text](<Screenshot 2024-03-27 200502.png>)
![alt text](<Screenshot 2024-03-27 201106.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
