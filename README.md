# www.offthugfashion.com
```
<html>
  <head>
    <title>Off Thug Fashion</title>
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Shop</a></li>
          <li><a href="#">About</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <h1>Welcome to Off Thug Fashion</h1>
      <p>Explore our latest fashion trends</p>
    </main>
    <footer>
      <p>&copy; 2025 Off Thug Fashion</p>
    </footer>
  </body>
</html>
```
CSS:
```
body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: space-between;
}

nav li {
  margin-right: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
}

main {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
  clear: both;
}
```
JavaScript:
```
// Add event listener to navigation links
document.querySelectorAll('nav a').forEach((link) => {
  link.addEventListener('click', (e) => {
    e.preventDefault();
    // Handle navigation link click
  });
});
```
