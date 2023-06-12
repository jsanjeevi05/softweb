# Ex.07 Software Product Company Website
## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

# layout.css:
```css
* {
  box-sizing: border-box;
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif ;
}
body{
    background-color: rgb(12, 12, 12);
    color: white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: hidden;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("C:\Users\SEC\Desktop\Web\product-images\pro4.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: white;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #2B2B2B;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color:rgb(180, 180, 179);
}

.menuitem a {
  text-decoration: dotted;
  color: rgb(180, 180, 179);
}

.content {
  display: block;
  width: 100%;
  min-height: 550px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-style:hidden;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align:justify;
  font-size: x-large;
}
.heading2{
  text-align:center;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 450px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  font-size:large;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #2B2B2B;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: rgb(180, 180, 179);
}
.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.peoplecontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.peoplecontent h1{
  text-align: left;
}

.peoplepics{
  display: block;
}

.peoplepic{
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.peoplepic img{
  width: 100px;
  height: 100px;
  display: block;
}

.peoplepic .peopleimage{
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.peoplepic .peoplename{
  display: block;
}

.peoplepic .peopledes{
  display: block;
}

.contactcontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;  
}

.contactitems{
  display: block;
}

.contactitem{
  display:block;
  text-align: left;
}

.contactitem .address{
  display: block;
  text-align: left;
}

.contactitem .number{
  display: block;
  text-align: left;
}

.conatctitem .email{
  display: block;
  text-align: left; 
}

.conatctitem .socials{
  display: block;
  text-align: left; 
}
 ```
 
 # home.html:
 ```html
 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMIN' IS NOT A CRIME</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="C:\Users\SEC\Desktop\Web\product-images\pro4.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1><u>About</u></h1>
          <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\pro3.png" alt="digi" />
          <div class="contenttext"> 
            Gamer's world has a huge range of gaming accessories and devices that can better your gaming experience by making it more user-friendly, enjoyable, and truly immersive. Shop for gaming accessories at the best possible prices, right here at Reliance Digital, to ensure you get the best possible deals for all your electronics.
            <br/>
            We empower the business with our intricate tools that are generally time comsuming to customize, easily available
            and compatable to multiple softwares to deliver unprecedented levels of performance and customer delight. 
            <br/>
            Our always-improving agenda drives the continuous development and creation of newer tools with hyper-realistic 
            details and unimaginable colours using the user preference and modification data, for better expirience.
            <br/>
            <h1><u>Every Gamers' wish </u></h1>
            <br>
            In the past 6 years, Digitrove has stayed as a vital resourse platform for all buyers. 
           <br/>
            Our mission is to provide high end softwares and application tools compatable with foregin softwares
            for gamers to enter heaven of gaming with ease and comfort.
            <h1><u>Features</u></h1>
            <ul>
              <li>Best accessories compbatible with upto 12th gen configuratons</li>
              <li>Licenced and Open sourse products with installed high level configurations</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Gamer'sworld.MGamers.org, Developed by Sanjeevi J.
      </div>
    </div>
  </body>
</html>
```

# products.html:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMIN' IS NOT A CRIME</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="C:\Users\SEC\Desktop\Web\product-images\pro4.png"type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">
          <h2 class="heading2">OUR PREMIUM PRODUCTS</h2>
          <h2 class="heading2"><u>Gaming monitors</u></h2>
          <div class="productitems">
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product1.png" alt="product 1">
              </div>
              <div class="itemname"> TUF Gaming</div>
              <div class="itemprice">Price: Rs.119,446.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product2.png" alt="product 2">
              </div>
              <div class="itemname">Samsung </div>
              <div class="itemprice">Price: Rs.110,550</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product3.png" alt="product 3">
              </div>
              <div class="itemname">Benq</div>
              <div class="itemprice">Price: Rs.98,000</div>
            </div>
            <br/>
            <h2 class="heading2"><u>Gaming keyboards</u></h2>
            <br/>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product4.png" alt="product 4">
              </div>
              <div class="itemname">sparky</div>
              <div class="itemprice">Price: Rs 5899</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product5.png" alt="product 5">
            </div>
            <div class="itemname">glider</div>
            <div class="itemprice">Price: Rs 4599</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product6.png" alt="product 6">
            </div>
            <div class="itemname">knight's</div>
            <div class="itemprice">Price: Rs 6999</div>
          </div>
          <br>
          <h2 class="heading2"><u>mouse</u></h2>
          <br>
          <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product7.png" alt="product 7">
              </div>
              <div class="itemname">Asus Rog</div>
              <div class="itemprice">Price: Rs.1999.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product8.png"alt="product 8">
              </div>
              <div class="itemname">Glitz-Pink</div>
              <div class="itemprice">Price: Rs.1900.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product9.png" alt="product 9">
              </div>
              <div class="itemname">Glitz-Black</div>
              <div class="itemprice">Price: Rs.1895.00</div>
            </div>
            <br/>
            <h2 class="heading2"><u>Play stations</u></h2>
            <br/>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product10.png" alt="product 10">
              </div>
              <div class="itemname">Ps6</div>
              <div class="itemprice">Price: Rs.1,05,975.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product11.png" alt="product 11">
              </div>
              <div class="itemname">Ps5</div>
              <div class="itemprice">Price: Rs.55,975.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\product12.png" alt="product 12">
              </div>
              <div class="itemname">ps4</div>
              <div class="itemprice">Price: Rs.45,975.00</div>
            </div>
          </div>
        </div>
      </div>      
      <div class="footer">
        Copyright &#169;2023 Gamer'sworld.MGamers.org, Developed by Sanjeevi J.
      </div>
    </div>
  </body>
</html>
```

# people.html:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMIN' IS NOT A CRIME</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="C:\Users\SEC\Desktop\Web\product-images\pro4.png" type="image/x-icon" />
  </head>

  <body>
   <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      <div>
            <h1>Our Team</h1>
            <div class="peopleitems">
                <div class="peopleitem">
                    <div class="peopleimage">
                    <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\peo1.jpg" alt="people1 image">
                    </div>
                    <div class="peoplename">MR.Deniz</div>
                    <div class="peoplepos">MD and CEO</div>
                </div>
                <div class="peoplecontent"> 
                  <div class="peopleitems">
                      <div class="peopleitem"> 
                          <div class="peopleimage">
                          <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\peo2.jpg"alt="people2 image">
                          </div>
                          <div class="peoplename">MR.Albert</div>
                          <div class="peoplepos">CPO</div>
                      </div>
                      <div class="peoplecontent">  
                        <div> class="peopleitems">
                            <div class="peopleitem"> 
                                <div class="peopleimage">
                                <img src="C:\Users\SEC\Desktop\Web\productcompanywebsite\peo3.png" alt="people3 image">
                                </div>
                                <div class="peoplename">MS.Filiz</div>
                                <div class="peoplepos">CHRO</div>
                            </div>
                        </div>
                        <div class="peoplecontent">  
                                                                    <div class="peopleitems">
                                        <div class="peopleitem"> 
                                            <div class="peopleimage">
                                            <img src="C:\Users\SEC\Documents\WhatsApp Image 2022-12-02 at 12.46.29.jpg" alt="people4 image">
                                            </div>
                                            <div class="peoplename">MR.Sylvester</div>
                                            <div class="peoplepos">Joint MD and CTO</div>
                              </div>
                        <div class="peoplecontent"> 
                                           <div class="peopleitems">
                                              <div class="peopleitem"> 
                                                  <div class="peopleimage">
                                                  <img src="./images/peo5.jpg" alt="people5 image">
                                                  </div>
                                                  <div class="peoplename">MR.William</div>
                                                  <div class="peoplepos">Head,Retail Sales</div>
                                                 </div>
                                            </div>     
                               <div class="peoplecontent">    
                                    <div class="peopleitems">
                                    <div class="peopleitem"> 
                                        <div class="peopleimage">
                                        <img src="./images/peo6.jpg" alt="people6 image">
                                        </div>
                                        <div class="peoplename">Ms.Olivia</div>
                                        <div class="peoplepos">CFO</div>
                     </div>  
             </div>
        </div>
      <div>
      <div class="footer">
        Copyright &#169; 2023 Gamer'sworld.MGamers.org, Developed by Sanjeevi J.
     </div>
     </body>
</html>
```

# contact.html:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>GAMIN' IS NOT A CRIME</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="C:\Users\SEC\Desktop\Web\product-images\pro4.png" type="image/x-icon" />    
    </head>
    <body>
        <div class="container">
            <div class="banner">
            </div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitem"><a href="/static/people.html">People</a></div>  
                <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="contactcontent">
                    <div class="contactitems">
                        <div class="contactitem">
                            <h2><u>Contact Us</u></h2>
                            <h3>Gloabal headquarters</h3>
                            <h3>Head Quarters-Chennai,India</h3>
                            <div class="address"> 60,Krishna Block Rajaji Salai,<br/>
                                Opp.Dist.Collectorate,<br/>
                                Chennai,<br/>
                                Tamil Nadu 600001</div>
                            <div class="number">phone: +91 57853 22746 </div>
                            <div class="email">E-mail: Gamer'sworldind@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-</div>
                            <h3>Regional Head Quarters-London,UK</h3>
                            <div class="address">42 Earlham St,<br/>
                                London WC2H 9LA,<br/>
                                 CA 94025,<br/>
                                 United Kingdom</div>
                            <div class="number">phone: +44 (0) 20 7234 3456 </div>
                            <div class="email">E-mail: Gamer'sworlduk@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-UK</div>
                            <h3>Regional Head Quarters-Seoul,South Korea</h3>
                            <div class="address">42 Teheran-ro 108-gil,  <br/>
                                Daechi-dong,<br/>
                                Gangnam-gu,Seoul,<br/>
                                South Korea</div>
                            <div class="number">phone: +82 2 312 3456 </div>
                            <div class="email">E-mail: Gamer'sworldsk@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-Kor</div>
                            <h3>Regional Head Quarters</h3>
                            <div class="address">1 Hacker Way,<br/>
                                 Menlo Park,<br/>
                                 CA 94025,<br/>
                                 United States</div>
                            <div class="number">phone: +1 650-543-4834 </div>
                            <div class="email">-mail: Gamer'sworldusa@MGamers.org</div>
                            <div class="socials">Instagram/Twitter/Facebook: @-=Gamer's world=-USA</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2023 Gamer'sworld.MGamers.org, Developed by Sanjeevi J.
            </div>
        </div>
    </body>

</html>
```
## OUTPUT:

### Home Page:
![ex71](https://user-images.githubusercontent.com/119390227/215340858-c29f82d6-dbf1-4c1f-9285-9e79f3379bda.png)



### product page:
![ex72](https://user-images.githubusercontent.com/119390227/215340887-4af82829-dc3b-4fb4-925d-ac73e022a9d4.png)



### people page:
![ex73](https://user-images.githubusercontent.com/119390227/215340913-6fdd39d0-00e5-453c-8128-b4f4847d3553.png)



### contact page
![ex74](https://user-images.githubusercontent.com/119390227/215340950-282bcda3-c0c5-4f6f-8202-233498481628.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.


## OUTPUT:


## HTML VALIDATOR:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
