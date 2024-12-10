# medinova
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Medical Bookstore</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Medical Bookstore</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="cart.html">Cart</a></li>
                <li><a href="checkout.html">Checkout</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Available Medical Books</h2>
        <section class="books">
            <div class="book">
                <img src="images/book1.jpg" alt="Book 1">
                <h3>Book Title 1</h3>
                <p>Description of book 1</p>
                <button onclick="addToCart('Book 1')">Add to Cart</button>
            </div>
            <div class="book">
                <img src="images/book2.jpg" alt="Book 2">
                <h3>Book Title 2</h3>
                <p>Description of book 2</p>
                <button onclick="addToCart('Book 2')">Add to Cart</button>
            </div>
            <!-- Add more books here -->
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Medical Bookstore</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
