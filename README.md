### HTML AND CSS PAGE TO RE-CREATE THE IMAGE

### AIM:
To re-create a HTML and CSS page based on the given image.

### HTML CODE
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">ROOPTECH</div>
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">PRODUCTS</a></li>
                <li><a href="#">PEOPLE</a></li>
                <li><a href="#" class="active">CONTACT</a></li>
            </ul>
            <div class="search-container">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>
    <main>
        <div class="contact-container">
            <div class="contact-form">
                <h2>Contact Us</h2>
                <form>
                    <input type="text" name="name" placeholder="Your Name">
                    <input type="email" name="email" placeholder="Your Email">
                    <button type="submit">Submit</button>
                </form>
            </div>
            <div class="contact-info">
                <h2>Contact Information</h2>
                <p><strong>Address:</strong> 3RD Floor, Tower 12, FCA Building, No. 18, ROOP DEVELOP CITY Phase-I, SECUNDERABAD HR IN 1888546</p>
                <p><strong>Email:</strong> rooptech.official@gmail.com</p>
                <p><strong>Phone:</strong> 1234567890</p>
            </div>
        </div>
    </main>
    <footer>
        <p>DESIGNED AND DEVELOPED BY KARTHICK (212221040072)</p>
    </footer>
</body>
</html>

~~~
### CSS CODE
~~~
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: url('background-image.jpg') no-repeat center center fixed;
    background-size: cover;
    color: white;
}

header {
    background: black;
    padding: 10px 20px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav .logo {
    font-size: 24px;
    font-weight: bold;
    color: rgb(93, 10, 209);
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a.active {
    color: rgb(93, 10, 209);
}

.search-container {
    display: flex;
    align-items: center;
}

.search-container input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-container button {
    background: rgb(93, 10, 209);
    color: white;
    border: none;
    padding: 5px 10px;
    margin-left: 5px;
    border-radius: 3px;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
}

.contact-container {
    display: flex;
    justify-content: space-between;
    width: 70%;
    background: rgba(0, 0, 0, 0.7);
    padding: 20px;
    border-radius: 10px;
}

.contact-form, .contact-info {
    width: 45%;
    border: 1px solid white;
    padding: 20px;
    border-radius: 10px;
}

.contact-form h2, .contact-info h2 {
    margin-top: 0;
    color: white;
}

.contact-form form {
    display: flex;
    flex-direction: column;
}

.contact-form input {
    padding: 10px;
    margin: 10px 0;
    border: none;
    border-radius: 5px;
}

.contact-form button {
    padding: 10px;
    border: none;
    border-radius: 5px;
    background: rgb(93, 10, 209);
    color: white;
    cursor: pointer;
}

footer {
    background: rgb(93, 10, 209);
    padding: 10px;
    text-align: center;
}
body{
    background-image: url(back.jpg);
}

~~~
### OUTPUT

![image](https://github.com/karthick-2003-coder/CSS-PROJECT/assets/135232854/168d9f9e-1ad4-4cb0-baf0-18197c5ca316)

### RESULT:
Thus the program has been completed successfully.
