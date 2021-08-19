# business-card-example
Just practicing how to create a business card 

<--! html-->
<div class="container">
  <h1 id="name">Patty Cake</h1>
  <h2 id="job">CakeShop</h2>
  <div class="contact">
     <span id="email">
        ✉️ CShop@cakeshop.com
    </span>
    <div id="address">
      <span>9000 Utopia Parkway</span>
      <br />
      <span>NYC, NY 10842</span>
    </div>
  </div>
</div>

*/ CSS*/
.container {
  height: 200px;
  width: 480px;
  margin: 15px;
  border: 1px solid grey;
  border-radius: 10px;
  background-color: PaleTurquoise;
}

#name {
  font-size: 32px;
  font-family: helvetica, sans-serif;
  text-shadow: 2px 1px #d3d3d3;
  text-align: center;
  margin-top: 10px;
  color: Hotpink;
}

#job {
  font-size: 30px;
  font-family: "Comic Sans MS", sans-serif;
  text-align: center;
  color: Hotpink;
  margin: 5px;
}

.contact {
  padding: 24px;
  margin-bottom: 32px;
  font-size: 16px;
}

#email {
  font-family: fantasy, sans-serif;
  color: Midnightblue;
}

#address {
  float: right;
  font-family: fantasy,sans-serif;
  color: Midnightblue;
}
