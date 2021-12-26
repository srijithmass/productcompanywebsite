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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
LAYOUT CSS:
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(0, 0, 0);
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/banner1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #1eff00;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #1eff00;
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
  color: #ffffff;
}

.menuitem a {
  text-decoration: none;
  color: #ffffff;
}

.content {
  display: block;
  width: 100%;
  background-image: url("/static/img/QQQ2.jpg");
  min-height: 500px;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: black;
  display: inline;
}
.homecontent h1 {
  color: white;
  display: inline;
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color: rgb(255, 255, 255);
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  display: inline;
  color: black;
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
  display: inline-block;
}
.productitem .itemimage {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: rgb(253, 249, 249);
  font-family: block;
}
.productitem .itemprice {
  display: block;
  color: rgb(255, 255, 255);
  font-family: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #1eff00;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #ffffff;
}
```
HOME PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Activision Blizzard Entertainment</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/office.jpg" alt="Building" />
          <div class="contenttext">
            Activision Publishing, Inc. is an American video game publisher based in Santa Monica, California. It serves as the publishing business for its parent company, Activision Blizzard, and consists of several subsidiary studios. Activision is one of the largest third-party video game publishers in the world and was the top United States publisher in 2016.
            <br><br>
            The company was founded as Activision, Inc. in October 1979 in Sunnyvale, California, by former Atari game developers, upset at how they were treated at Atari, to develop their own games for the popular Atari 2600 home video game console. Activision was the first independent, third-party, console video game developer. The 1983 video game crash, in part created by too many new companies trying to follow in Activision's footsteps without the expertise of Activision's founders, hurt Activision's position in console games, forcing them to diversify into games for home computers, including the acquisition of Infocom. After a management shift, with CEO Jim Levy replaced by Bruce Davis, the company renamed itself as Mediagenic and branched out into business software applications. Mediagenic quickly fell into debt, and the company was bought for around US$500,000 by Bobby Kotick and a small group of investors around 1991.
            <br><br>
            Kotick instituted a full rework of the company to cover its debts: dismissing most of its staff, moving the company to Los Angeles, and reverting to the Activision name. Building on existing assets, the Kotick-led Activision pursued more publishing opportunities and, after recovering from the former debt, started acquiring numerous studios and intellectual properties over the 1990s and 2000s, among these being the Call of Duty and Guitar Hero series. A holding company was formed as Activision's parent company to manage the internal and acquired studios. In 2008, this holding company merged with Vivendi Games (the parent company of Blizzard Entertainment) and formed Activision Blizzard, with Kotick as its CEO. Within this structure, Activision serves to manage numerous third-party studios and publish all the parent company's games outside those created by Blizzard.     
            
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Activision Blizzard Entertainment, Developed by <a href="//linktr.ee/srijithmass">SRIJITH R</a>
      </div>
    </div>
  </body>
</html>
```
PEOPLE PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Activision Blizzard Entertainment</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/1.jpg" alt="product image">
                </div>
                <div class="itemname">Bobby Kotick</div>
                <div class="itemprice">CEO</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/2.jpeg"  alt="product image">
                </div>
                <div class="itemname">Beluga</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/3.jpg"  alt="product image">
              </div>
              <div class="itemname">Khaby Lame</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/4.png"  alt="product image">
              </div>
              <div class="itemname">Melvin Lawson</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/5.jfif"  alt="product image">
            </div>
            <div class="itemname">Risitas</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/6.jfif"  alt="product image">
          </div>
          <div class="itemname">Xavier</div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Activision Blizzard Entertainment, Developed by <a href="//linktr.ee/srijithmass">SRIJITH R</a>
  </div>
</body>
</html>
```
CONTACTUS PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Activision Blizzard Entertainment</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
           3100 Ocean Park,<br>
           Boulevard Santa Monica,<br>
           CA 90405,<br>
           USA<br>
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mr.Khaby Lame (MARKETING MANAGER): 8220156869<br><br>
              Mr.Ricardo Milos (OPERATION MANAGER) : 9865432145<br><br>
              Mr.Xavier (OFFICE MANAGER) : 6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:activitionentertainment2021@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Activision Blizzard Entertainment, Developed by <a href="//linktr.ee/srijithmass">SRIJITH R</a>
      </div>
    </div>
  </body>
</html>
```
PRODUCTS PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Activision Blizzard Entertainment</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/destiny.jpg" alt="product image">
                  </div>
                  <div class="itemname">Destiny</div>
                  <div class="itemprice">Price: Rs.999/- </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Crash.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Crash Bandicoot N. Sane Trilogy</div>
                  <div class="itemprice">Price: Rs.2000/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/cod warzone.jpg"  alt="product image">
                </div>
                <div class="itemname">Call of Duty: Warzone</div>
                <div class="itemprice">Price: Rs.3000/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/cod-mw.jpg"  alt="product image">
                </div>
                <div class="itemname">Call of Duty: Modern Warfaren</div>
                <div class="itemprice">Price: Rs.3999/- </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/cod black ops.jpg"  alt="product image">
              </div>
              <div class="itemname">Call of Duty: Black Ops</div>
              <div class="itemprice">Price: Rs.8950/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/guitar hero.jpg"  alt="product image">
            </div>
            <div class="itemname">Guitar Hero: Van Halen</div>
            <div class="itemprice">Price: Rs.2070/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/Cabela's Survival.jpg"  alt="product image">
            </div>
            <div class="itemname">Cabela's Survival: Shadows of Katmai</div>
            <div class="itemprice">Price: Rs.3270/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/prototype.jfif"  alt="product image">
            </div>
            <div class="itemname">Prototype</div>
            <div class="itemprice">Price: Rs.5570/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/Sekiro.jpg"  alt="product image">
            </div>
            <div class="itemname">Sekiro</div>
            <div class="itemprice">Price: Rs.9550/- </div>
        </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/Madagascar.jpg"  alt="product image">
        </div>
        <div class="itemname">Madagascar</div>
        <div class="itemprice">Price: Rs.1080/- </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/marvel.png"  alt="product image">
        </div>
        <div class="itemname">Ultimate Alliance</div>
        <div class="itemprice">Price: Rs.2000/- </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/skylanders.jpg"  alt="product image">
        </div>
        <div class="itemname">Skylanders</div>
        <div class="itemprice">Price: Rs.2300/- </div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Activision Blizzard Entertainment, Developed by <a href="//linktr.ee/srijithmass">SRIJITH R</a>
      </div>
    </div>
  </body>
</html>
```


## OUTPUT:

### Home Page:

![output](./images/Screenshot_(1).png)
![output](./images/Screenshot_(2).png)
![output](./images/Screenshot_(3).png)
![output](./images/Screenshot_(4).png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
