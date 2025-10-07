[about.html](https://github.com/user-attachments/files/22736506/about.html)
<html>
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Sudip Singh | About</title>
<link rel="stylesheet" href="style.css" />
</head>
<body>
<header>[script.js](https://github.com/user-attachments/files/22736511/script.js)
[sudip.html](https://github.com/user-attachments/files/22736510/sudip.html)
[style.css](https://github.com/user-attachments/files/22736509/style.css)
[index.html](https://github.com/user-attachments/files/22736508/index.html)
[contact.html](https://github.com/user-attachments/files/22736507/contact.html)

  <h1>Sudip Singh</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html" class="active">About</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>
<div class="container">
  <section id="about">
    <h2>About Me</h2>
    <div class="about">
      <p>Name : Sudip Singh<br>
        Date of birth : 2068/09/25<br>
        Father's Name : Laxendra Singh<br> <A href="index.html">
      <img src="sudip.jpg" Align= "right" Title="Return to homepage"></A>
        Mother's Name : Pushpa Singh<br>
        Sex : Male<br>
        Martial Status : Unmarried<br>
        Nationality : Nepali<br>
        Parmanent   Address : Bhajhang, Nepal<br>
        Temporary Address : Changathali,Lalitpur,Nepal<br>
        Contact no : 9846741239<br>
        E-mail Address : sudip39pro@gmail.com<br>
        Facebook : <A href="https://www.facebook.com/search/top?q=sudip%20singh">Sudip Singh<br>
      </p>
    </div>
  </section>
</div>
</body>
</html>

<html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Sudip Singh | Contact</title>
<link rel="stylesheet" href="style.css" />
</head>
<body>

<header>
  <h1>Sudip Singh</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html" class="active">Contact</a>
  </nav>
</header>

<div class="container">
  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact">
      <form>
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Send</button>
      </form>
    </div>
  </section>
</div>

</body>
</html>

<html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Sudip Singh | Home</title>
<link rel="stylesheet" href="style.css" />
</head>
<body class="bugatti-bg">
<header>
  <b><h1>Sudip Singh</h1></b>
  <nav>
 <a href="index.html" class="active">Home</a>
 <a href="about.html">About</a>
 <a href="contact.html">Contact</a>
 </nav>
</header>
<div class="container">
  <section id="home">
 <h2>Home</h2>
 <p>Welcome to my personal website. I am Sudip Singh and I am interested in mechanism of different electronics.<br> In this site I am going to provide some information of myself through showcasing my skills in coding. I have<br> divided the topics in three sections (home, about and contact). <br>  </p>
</div>
</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Helvetica Neue', sans-serif;
  line-height: 1.7;
  color: #456789;
  background-color: #0D1B2A;
}

header {
  background-color: #9A1E8D;
  color: #fff;
  padding: 2rem;
  text-align: center;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
}
header h1 {
  font-size: 2.8rem;
  letter-spacing: 2px;
  font-weight: 700;
}
nav {
  margin-top: 1rem;
}
nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 0.8rem;
  padding: 0.4rem 1rem;
  border-radius: 20px;
  background-color: #5A189A;
  transition: all 0.3s;
}
nav a:hover,
nav a.active {
  background-color: #FF6F00;
  transform: scale(1.1);
  box-shadow: 0 0 10px rgba(255, 111, 0, 0.4);
}

.container {
  max-width: 1000px;
  margin: 2rem auto;
  padding: 2rem;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
  backdrop-filter: blur(10px);
  transition: all 0.3s;
}
.container:hover {
  transform: translateY(-5px);
}

section h2 {
  color: #1E90FF;
  margin-bottom: 0.8rem;
  font-size: 2rem;
  border-bottom: 3px solid #FF6F00;
  display: inline-block;
  padding-bottom: 0.3rem;
  letter-spacing: 1px;
}


.about {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 11rem;
  background: #A3E635; 
  border-radius: 15px;
  padding: 1rem;
}

.about img {
  width: 200px;
  height: 250px;
  object-fit: cover;
  border: 4px solid #FF6F00;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
  display: block;
  margin-right: auto;
  margin-left: 0;
}

.about p {
  flex: 1;
  font-size: 1.1rem;
  background: rgba(255, 255, 255, 0.6);
  padding: 1rem;
  border-radius: 10px;
  color: #222222;
}

.contact form {
  max-width: 600px;
  display: flex;
  flex-direction: column;
}
.contact label {
  margin-top: 0.5rem;
  margin-bottom: 0.3rem;
  font-weight: 600;
  color: #5A189A;
}
.contact input,
.contact textarea {
  padding: 0.7rem;
  border: 2px solid #1E90FF;
  border-radius: 10px;
  margin-bottom: 1rem;
  background: rgba(255, 255, 255, 0.7);
  box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: border-color 0.3s, box-shadow 0.3s;
}
.contact input:focus,
.contact textarea:focus {
  border-color: #FF6F00;
  box-shadow: 0 0 10px rgba(255, 111, 0, 0.4);
  outline: none;
}
.contact button {
  background-color: #FF6F00;
  color: #fff;
  padding: 0.8rem;
  border: none;
  cursor: pointer;
  border-radius: 30px;
  font-weight: 700;
  letter-spacing: 1px;
  transition: all 0.3s;
}
.contact button:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 20px rgba(255, 111, 0, 0.5);
}

section {
  margin-bottom: 2.5rem;
}

@media (max-width: 600px) {
  .about {
    flex-direction: column;
    text-align: center;
  }
  .about img {
    margin: 0 auto;
  }
  header h1 {
    font-size: 2.2rem;
  }
}

@media print {
  * {
    -webkit-print-color-adjust: exact;
    print-color-adjust: exact;
  }

  nav,
  header {
    display: none; 
  }

  body {
    background: #ffffff;
    color: #222;
  }

  .container {
    box-shadow: none;
    background: #fff;
  }

  .about img {
    float: right;
    margin: 0 0 1rem 1rem;
  }
}

<html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Sudip Singh | Contact</title>
  <link rel="stylesheet" href="styles.css">
  <!-- Live Chat widget script placeholder -->
  <!-- You can use Tawk.to, or other free live chat service -->
  <script src="https://embed.tawk.to/YOUR_TAWK_TO_ID/default" async></script>
</head>
<body>
  <header>
    <h1>Sudip Singh</h1>
    <p>Digital Presentation Maker & Consultant</p>
    <nav>
      <a href="about.html">About</a>
      <a href="index.html">Contact</a>
    </nav>
  </header>
  
  <section class="visitor-counter">
    <p>Number of visitors: <span id="visitorCount">0</span></p>
  </section>
  
  <section class="contact-section">
    <h2>Contact Me</h2>
    <form id="contactForm" method="POST" action="YOUR_FORM_ENDPOINT">
      <label>
        Your Name:<br>
        <input type="text" name="name" required>
      </label><br>
      <label>
        Your Email:<br>
        <input type="email" name="email" required>
      </label><br>
      <label>
        Message:<br>
        <textarea name="message" rows="5" required></textarea>
      </label><br>
      
      <!-- CAPTCHA -->
      <div id="captchaContainer">
        <label for="captchaInput">Enter the text:</label><br>
        <canvas id="captchaCanvas" width="200" height="60"></canvas><br>
        <input type="text" id="captchaInput" placeholder="Enter CAPTCHA" required>
        <button type="button" id="refreshCaptcha">Refresh CAPTCHA</button>
      </div><br>
      
      <button type="submit">Send Message</button>
    </form>
    
    <div class="direct-links">
      <p>Email: <a href="mailto:sudip39pro@gmail.com">sudip39pro@gmail.com</a></p>
      <p>Instagram: <a href="https://instagram.com/sudipxcx" target="_blank">@sudipxcx</a></p>
    </div>
  </section>
  
  <footer>
    <p>&copy; 2025 Sudip Singh | Lalitpur, Nepal</p>
  </footer>
  
  <script src="script.js"></script>
</body>
</html>

