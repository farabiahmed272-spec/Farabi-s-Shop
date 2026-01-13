<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farabi Shop - Clothing Store</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; text-align: center; padding: 20px; }
        nav { background-color: #444; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        .container { max-width: 1200px; margin: 20px auto; padding: 20px; background: white; border-radius: 8px; }
        .products { display: flex; flex-wrap: wrap; justify-content: space-around; }
        .product { width: 300px; margin: 20px; text-align: center; border: 1px solid #ddd; padding: 10px; border-radius: 8px; }
        .product img { width: 100%; height: 200px; object-fit: cover; }
        footer { background-color: #333; color: white; text-align: center; padding: 10px; margin-top: 20px; }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Farabi Shop</h1>
        <p>Your go-to place for stylish clothing!</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="home">
        <h2>Featured Products</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=T-Shirt" alt="T-Shirt">
                <h3>Cotton T-Shirt</h3>
                <p>$19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Jeans" alt="Jeans">
                <h3>Denim Jeans</h3>
                <p>$49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200?text=Jacket" alt="Jacket">
                <h3>Leather Jacket</h3>
                <p>$89.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>
    <div class="container" id="about">
        <h2>About Farabi Shop</h2>
        <p>Farabi Shop offers high-quality, trendy clothing for men, women, and kids. We focus on comfort, style, and affordability. Visit us today!</p>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@farabishop.com</p>
        <p>Phone: +1 (123) 456-7890</p>
        <p>Address: 123 Fashion Street, City, Country</p>
    </div>
    <footer>
        <p>&copy; 2023 Farabi Shop. All rights reserved.</p>
    </footer>
    <script>
        // Simple alert for "Add to Cart" buttons (expand with real cart logic)
        document.querySelectorAll('button').forEach(btn => {
            btn.addEventListener('click', () => alert('Added to cart!'));
        });
    </script>
</body>
</html>
