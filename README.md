# Bhasker-milk-centre
Milk centre in malapally Nizamabad where you can get all dairy items 


<!DOCTYPE html>
<html>
<head>
  <title>BHASKER MILK CENTRE</title>

  <style>
    body {
      font-family: Arial;
      background: #f5f5f5;
      text-align: center;
    }

    h1 {
      background: black;
      color: white;
      padding: 15px;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .product {
      border: 1px solid #ccc;
      background: white;
      margin: 10px;
      padding: 15px;
      width: 200px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      border-radius: 10px;
    }

    button {
      background: #25D366;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background: #1ebc59;
    }
  </style>
</head>

<body>

<h1>My Modern Store</h1>
<p>Order directly on WhatsApp</p>

<div class="container">

  <div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>T-Shirt</h3>
    <p>Price: ₹499</p>
    <button onclick="order('T-Shirt ₹499')">Order Now</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>Shoes</h3>
    <p>Price: ₹999</p>
    <button onclick="order('Shoes ₹999')">Order Now</button>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>Watch</h3>
    <p>Price: ₹799</p>
    <button onclick="order('Watch ₹799')">Order Now</button>
  </div>

</div>

<p>📞 Contact: +91 9876543210</p>

<script>
function order(product) {
  let number = "919876543210"; // apna number daal
  let message = "Hello, I want to order: " + product;
  let url = "https://wa.me/" + number + "?text=" + encodeURIComponent(message);
  window.open(url, '_blank');
}
</script>

</body>
</html>