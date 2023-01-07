Create a simple navigation bar with a logo on the left and a menu on the right. The navigation bar should be fixed to the top of the page and span the full width of the page.

Style the navigation bar with a solid color background and white text.

Add hover states to the menu items so that they change color when the user hovers over them.

Create a hero section with a full-width image and a call-to-action button centered on top of the image.

Add a responsive layout to the hero section so that the image and button stack vertically on mobile devices.

Create a grid of product cards, each with an image, title, and price.

Add hover states to the product cards so that the image becomes slightly opaque when the user hovers over it.

Add a footer to the page with social media links and a newsletter sign-up form.

Here is some sample HTML and CSS code that you can use as a starting point for this exercise:

```
<!-- Navigation bar -->
<nav>
  <div class="logo">Logo</div>
  <ul class="menu">
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>

<!-- Hero section -->
<section class="hero">
  <img src="hero-image.jpg" alt="Hero image">
  <button class="cta">Sign up now</button>
</section>

<!-- Product grid -->
<div class="product-grid">
  <div class="product">
    <img src="product-image.jpg" alt="Product image">
    <h3 class="product-title">Product Title</h3>
    <p class="product-price">$99.99</p>
  </div>
  <!-- Add additional product cards here -->
</div>

<!-- Footer -->
<footer>
  <div class="social-links">
    <a href="#">Facebook</a>
    <a href="#">Twitter</a>
    <a href="#">Instagram</a>
  </div>
  <form class="newsletter-form">
    <input type="email" placeholder="Email address">
    <button>Sign up</button>
  </form>
</footer>
```

```
/* Navigation bar */
nav {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  background-color: #333;
  color: #fff;
  display: flex;
  align-items: center;
  height: 60px;
}

.logo {
  font-size: 18px;
  font-weight: bold;
  margin-left: 20px;
}

.menu {
  margin-left: auto;
  margin-right: 20px;
  display: flex;
}

.menu li {
  list-style: none;
  margin-left: 20px;
}

.menu a {
  color: #fff;
```