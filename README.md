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
### layout.css
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>invensys Private Limited</title>

     <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">

  </head>

  <body>
    <div class="container">
      <div class="banner">invensys Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">   
          <h1>PEOPLE AT invensys</h1>
          <div class="productitems">
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/images/people1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Rafi Moran</div>
                  <div class="itemprice">President & CEO</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/images/people2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Uri Heiman</div>
                  <div class="itemprice">Executive Vice President Operations</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/images/people3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Hernan Garber</div>
                  <div class="itemprice">Executive Vice President, Business Development & Marketing</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/images/people4.jpg" alt="product image">
                  </div>
                  <div class="itemname">Vered Yishay</div>
                  <div class="itemprice">Executive Vice President Product Management and Development</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/images/people5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Tsachi Gal</div>
                  <div class="itemprice">Vice President, Finance & CFO</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/images/people6.jpg" alt="product image">
                  </div>
                  <div class="itemname">Feng Yu</div>
                  <div class="itemprice">ETS Associate Vice President of Global TOEIC Management</div>
              </div>

          </div>
          </div>       
      </div>
      <div class="footer">
        Copyright &#169; 2023 invensys Limited, Developed by sharangini T K
      </div>
    </div>
  </body>
</html>
```
### home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/html/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/html/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by sharangini.
      </div>
    </div>
  </body>
</html>
```
### product.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by sharangini
      </div>
    </div>
  </body>
</html>
```
### people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>

     <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">

  </head>

  <body>
    <div class="container">
      <div class="banner">EdoSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">   
          <h1>PEOPLE AT invensys</h1>
          <div class="productitems">
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/people1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Rafi Moran</div>
                  <div class="itemprice">President & CEO</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/people2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Uri Heiman</div>
                  <div class="itemprice">Executive Vice President Operations</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/people3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Hernan Garber</div>
                  <div class="itemprice">Executive Vice President, Business Development & Marketing</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/people4.jpg" alt="product image">
                  </div>
                  <div class="itemname">Vered Yishay</div>
                  <div class="itemprice">Executive Vice President Product Management and Development</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/people5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Tsachi Gal</div>
                  <div class="itemprice">Vice President, Finance & CFO</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/people6.jpg" alt="product image">
                  </div>
                  <div class="itemname">Feng Yu</div>
                  <div class="itemprice">ETS Associate Vice President of Global TOEIC Management</div>
              </div>

          </div>
          </div>       
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by sharangini.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:
![k](https://github.com/shara56/softweb/assets/113497104/d329d6d2-5488-49bc-b12c-ecefe3255a54)
![k1](https://github.com/shara56/softweb/assets/113497104/8b0e81f6-d3e1-4581-8ea7-9824f71989cd)
![k2](https://github.com/shara56/softweb/assets/113497104/b5d3c347-9f03-495f-96bc-ecac345bf957)
## SERVER OUTPUT:
![k3](https://github.com/shara56/softweb/assets/113497104/9a3f1a5a-8c1d-49f3-891b-3fccccc97bbc)
## HTML VALIDATOR:
![k4](https://github.com/shara56/softweb/assets/113497104/7489d03d-5b99-44f1-b5e8-3bc3bed76d06)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
