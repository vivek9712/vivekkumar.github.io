# vivekkumar.github.io
<html>

<head>
    <title>Vivek iphone store </title>
    <link rel="icon" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRtCvzywKMRutNPDeHr43ZTP9KwzBHdcDQaRA&usqp=CAU" type="image/icon type">
    <link rel="stylesheet" href="./iphone page.css">
  <style>
    @import url('https://fonts.googleapis.com/css?family=Roboto:100,300,400,700&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'roboot', sans-serif;
  text-decoration: none;
}
nav {
  width: 100%;
  height: 48px;
  background: #000;
  display: flex;
  justify-content: center;
  align-items: center;
}
nav ul {
  list-style: none;
  display: flex;
}
nav ul li {
  margin: 0 40px;
}
nav ul li a {
  font-weight: 300;
  color: #adadad;
  transition: 600ms;
}
nav ul li a:hover {
  color: #f5f5f7;
}

/*--- section welcome ---*/
.welcome {
  width: 100%;
  height: 500px;
  background-image: url("https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/thai-aos-en-banner-hero-20160202?wid=1440&hei=689&fmt=jpeg&qlt=80&op_usm=0.5,0.5&.v=0");
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
}
.welcome h1 {
  color: #fff;
  font-weight: 300;
  font-size: 2rem;
}

/*--- section product ---*/
.product-mac,
.product-iphone,
.product-watch,
.product-ipad {
  width: 100%;
  height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 50px 0;
  cursor: pointer;
}
.product-mac h2,
.product-iphone h2,
.product-watch h2,
.product-ipad h2 {
  font-size: 2rem;
  font-weight: 300;
  margin-bottom: 20px;
}
.container {
  width: 1070px;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 15px;
}
.grid-product {
  background: #f1f1f1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  transition: .5s;
}
.grid-product:hover {
  background: #e1e1e1;
}
.grid-product img {
  width: 300px;
}
.grid-detail {
  margin: 20px 0;
  text-align: center;
}
.grid-detail p:last-child {
  transition: .5s;
  margin-top: 10px;
}
.grid-product:hover > .grid-detail p:last-child {
  color: #3498db;
}

/*-------*/
.grid-full {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
}
.grid-product-full {
  background: #f1f1f1;
  grid-column: span 3;
  display: flex;
  position: relative;
}
.grid-detail-sum {
  position: absolute;
  top: 35%;
  right: 12%;
  text-align: center;
}
.grid-detail-sum h2 {
  font-size: 3rem;
  font-weight: 500;
}
.grid-detail-sum p {
  margin: 20px 0;
}
.grid-detail-sum a {
  color: #3498db;
}
.grid-detail-sum a:hover {
  text-decoration: underline;
}

/*--- footer ---*/
footer {
  width: 100%;
  height: 500px;
  background: #f1f1f1;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.footer-main {
  width: 1070px;
}
.footer-detail {
  font-size: .7rem;
  color: #95a5a6;
  padding: 20px 0;
  border-bottom: 1px solid #bdc3c7;
}
.footer-detail a {
  color: #2c3e50;
}
.footer-detail a:hover {
  text-decoration: underline;
}
.footer-welcome {
  display: flex;
  margin: 20px 0;
  font-size: .8rem;
  color: #34495e;
}
.footer-welcome i {
  margin-right: 10px;
}
.footer-ul {
  display: flex;
  justify-content: space-between;
}
.footer-ul ul {
  list-style: none;
}
.footer-ul ul li {
  margin: 7px 0;
}
.footer-ul ul li h4 {
  color: #34495e;
  font-size: .7rem;
}
.footer-ul ul li a {
  color: #7f8c8d;
  font-size: .7rem;
}
.footer-ul ul li a:hover {
  text-decoration: underline; 
}
#mt {
  padding-top: 30px;
}
.footer-contact {
  border-bottom: 1px solid #bdc3c7;
  padding: 12px 0;
  margin: 10px 0;
  color: #7f8c8d;
  font-size: .7rem;
}
.footer-contact a {
  color: #3498db;
}
.footer-contact a:hover {
  text-decoration: underline;
}
.footer-copyright {
  color: #7f8c8d;
  font-size: .7rem;
  display: flex;
  justify-content: space-between;
}
.footer-copyright ul {
  display: flex;
  list-style: none;
  width: auto;
}
.footer-copyright ul li {
  margin: 0 10px;
}
.footer-copyright ul li a {
  color: #7f8c8d;
}
.footer-copyright ul li a:hover {
  text-decoration: underline; 
}
.vr {
  height: 15px;
  width: 1px;
  background: #bdc3c7;
}
.footer-lang {
  display: flex;
}
.footer-lang p {
  margin: 0 10px;
}
.circle {
  width: 15px;
  height: 15px;
}
.circle img {
  width: 100%;
  height: 100%;
  background-size: cover;
  border-radius: 50%;
}
  </style>
</head>

<body>
    <nav>
        <ul>
            <!-- <img src="./logo/online-shopping.jpg" class="logo"> -->
            <li><a href="#"><i class="fab fa-apple"></i></a></li>
            <li><a href="http://127.0.0.1:5500/online%20shooping/home%20page.html">Home</a></li>
            <li><a href="http://127.0.0.1:5500/online%20shooping/iphone%20page.html">iPhone</a></li>
            <li><a href="http://127.0.0.1:5500/online%20shooping/Samsung%20page.html">Samsung</a></li>
            <li><a href="#">Nokia</a></li>
            <li><a href="#">Motorola</a></li>
            <li><a href="#">Accessories</a></li>
            <li><a href="#">Service</a></li>  
            <li><a href="#"><i class="fas fa-search"></i></a></li>
            <li><a href="#"><i class="fas fa-shopping-bag"></i></a></li>
        </ul>
    </nav>

    <section class="welcome">
        <h1>Shop for your favorite Apple products.</h1>
    </section>

    <section class="product-mac">
        <div class="container">
            <h2>Mac</h2>
            <div class="grid">
                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/macbook-air-segment?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1573580916082">
                    <div class="grid-detail">
                        <p>MacBook Air</p>
                        <p>From ฿35,000</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/macbook-pro-segment-2019?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1573580916135">
                    <div class="grid-detail">
                        <p>MacBook Pro</p>
                        <p>From ฿42,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/imac-segment?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1570232081431">
                    <div class="grid-detail">
                        <p>iMac</p>
                        <p>From ฿37,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/imac-pro-segment?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1570231926191">
                    <div class="grid-detail">
                        <p>iMac Pro</p>
                        <p>From ฿172,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/mac-pro-segment?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1524766968633">
                    <div class="grid-detail">
                        <p>Mac Pro</p>
                        <p>From ฿114,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/mac-mini-segment?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1539466285370">
                    <div class="grid-detail">
                        <p>Mac mini</p>
                        <p>From ฿27,900</p>
                    </div>
                </div> <!--end grid-product-->
            </div> <!--end grid-->
        </div> <!--end container-->
    </section>


    <section class="product-iphone">
        <div class="container">
            <h2>iPhone</h2>
            <div class="grid">
                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/iphone-11-pro-segment-201909?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1567201566801">
                    <div class="grid-detail">
                        <p>iPhone 11 Pro</p>
                        <p>From ฿35,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/iphone-11-segment-201909?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1567201566851">
                    <div class="grid-detail">
                        <p>iPhone 11</p>
                        <p>From ฿24,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/iphone-xr-segment?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1535393884526">
                    <div class="grid-detail">
                        <p>iPhone XR</p>
                        <p>From ฿21,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/segment-hero-iphone-8-201709?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1504891668190">
                    <div class="grid-detail">
                        <p>iPhone 8</p>
                        <p>From ฿15,900</p>
                    </div>
                </div>
            </div> <!--end grid-->
        </div> <!--end container-->
    </section>



    <section class="product-watch">
        <div class="container">
            <h2>Watch</h2>
            <div class="grid">
                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/apple-watch-series-5-segment-201909?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1567038391208">
                    <div class="grid-detail">
                        <p>Apple Watch Series 5</p>
                        <p>From ฿13,400</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/apple-watch-nike-segment-201909?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1567202843775">
                    <div class="grid-detail">
                        <p>Apple Watch Nike</p>
                        <p>From ฿13,400</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/apple-watch-hermes-segment-201909?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1568373934272">
                    <div class="grid-detail">
                        <p>Apple Watch Hermes</p>
                        <p>From ฿40,900</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/apple-watch-edition-segment-201909?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1568066151825">
                    <div class="grid-detail">
                        <p>Apple Watch Edition Series 5</p>
                        <p>From ฿25,400</p>
                    </div>
                </div>

                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/apple-watch-series-3-segment-201909?wid=800&hei=600&fmt=png-alpha&qlt=80&.v=1567038391348">
                    <div class="grid-detail">
                        <p>Apple Watch Series 3</p>
                        <p>From ฿6,400</p>
                    </div>
                </div><!--end grid-product-->
            </div> <!--end grid-->
        </div> <!--end container-->
    </section>

    <section class="product-ipad">
        <div class="container">
            <h2>iPod and Apple TV</h2>
            <div class="grid-full">
                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/segment-hero-ipod-touch-201509?wid=400&hei=300&fmt=png-alpha&.v=1491260462715">
                    <div class="grid-detail">
                        <p>iPod Touch</p>
                        <p>Form ฿6,900</p>
                    </div>
                </div>
                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/segment-hero-apple-tv4k-201709?wid=400&hei=300&fmt=png-alpha&.v=1504891668090">
                    <div class="grid-detail">
                        <p>Apple TV 4K</p>
                        <p>Form ฿7,528</p>
                    </div>
                </div>
                <div class="grid-product">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/segment-hero-apple-tv4k-201709?wid=400&hei=300&fmt=png-alpha&.v=1504891668090">
                    <div class="grid-detail">
                        <p>Apple TV HD</p>
                        <p>Form ฿6,168</p>
                    </div>
                </div>
                <div class="grid-product-full">
                    <img
                        src="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/smb-accessories-201908?wid=1070&hei=480&fmt=png-alpha&.v=1563990869846">
                    <div class="grid-detail-sum">
                        <h2>Accessories</h2>
                        <p>get things done in style.</p>
                        <a href="#">shop now <i class="fas fa-chevron-right"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-main">
            <div class="footer-detail">
                <p>Prices are inclusive of VAT. Free delivery for all orders.</p>
                <p>*Total order value must be less than 30,000 THB. Admin fee may be charged by bank/processing entity
                    in addition to order value.</p>
                <p>**For approved customers only. Subject to approval. For more information, see <a
                        href="#">http://www.apple.com/th-en/help/payments.</a></p>
            </div> <!-- end footer detail -->

            <div class="footer-welcome">
                <i class="fab fa-apple"></i>
                <i class="fas fa-chevron-right"></i>
                <p>Welcome to the Vivek Apple Store</p>
            </div> <!-- end footer-welcome -->

            <div class="footer-ul">
                <ul>
                    <li>
                        <h4>Shop and Learn</h4>
                    </li>
                    <li><a href="http://127.0.0.1:5500/online%20shooping/home%20page.html">Home</a></li>
                    <li><a href="#">About us</a></li>
                    <li><a href="#">Search</a></li>
                    <li><a href="http://127.0.0.1:5500/online%20shooping/cart.html">Cart</a></li>
                    <li><a href="#">Checkout</a></li>
                </ul>

                <ul>
                    <li>
                        <h4>Apple Store</h4>
                    </li>
                    <li><a href="#">Apple Store App</a></li>
                    <li><a href="#">Financing</a></li>
                    <li><a href="#">Order Status</a></li>
                    <li><a href="#">Shopping Help</a></li>
                </ul>

                <ul>
                    <li>
                        <h4>For Education</h4>
                    </li>
                    <li><a href="#">Apple and Education</a></li>
                    <li><a href="#">Shop for College</a></li>
                    <li id="mt">
                        <h4>For Business</h4>
                    </li>
                    <li><a href="#">Apple and Business</a></li>
                    <li><a href="#">shop for Business</a></li>
                </ul>

                <ul>
                    <li>
                        <h4>Account</h4>
                    </li>
                    <li><a href="#">My Profile</a></li>
                    <li><a href="#">Change Password</a></li>
                    <li><a href="#">Order History</a></li>
                    <li><a href="#">My Whislist</a></li>
                    <li><a href="#">My Cashback</a></li>
                    <li id="mt">
                        <h4>Apple Values</h4>
                    </li>
                    <li><a href="#">Accessibility</a></li>
                    <li><a href="#">Environment</a></li>
                    <li><a href="#">Privacy</a></li>
                    <li><a href="#">Supplier Responsibility</a></li>
                </ul>

                <ul>
                    <li>
                        <h4>About Apple</h4>
                    </li>
                    <li><a href="#">Newsroom</a></li>
                    <li><a href="#">Investors</a></li>
                    <li><a href="#">Events</a></li>
                    <li><a href="#">Contact Apple</a></li>
                </ul>
            </div>

            <div class="footer-contact">
                <p>More ways to shop: visit an <a href="#">Vivek Apple Store, </a>Call 788-894-4066, or <a href="#">find
                        a seller</a></p>
            </div>
            <div class="footer-copyright">
                <p>Copyright © 2019 Vivek. All rights reserved.</p>

                <ul>
                    <li><a href="#">Privacy Policy</a></li>
                    <div class="vr"></div>
                    <li><a href="#">Terms of Use</a></li>
                    <div class="vr"></div>
                    <li><a href="#">Sales and Refunds</a></li>
                    <div class="vr"></div>
                    <li><a href="#">Legal</a></li>
                    <div class="vr"></div>
                    <li><a href="#">Sitemap</a></li>
                </ul>

                <div class="footer-lang">
                    <div class="circle">
                        <img
                            src="https://upload.wikimedia.org/wikipedia/en/thumb/4/41/Flag_of_India.svg/255px-Flag_of_India.svg.png">
                    </div>
                    <p>india</p>
                    <div class="vr"></div>
                    <p>Vivek</p>
                </div>
            </div>

        </div>
    </footer>
</body>

</html>
