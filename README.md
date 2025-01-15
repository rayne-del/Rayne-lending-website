# Rayne-lending-website
loan services
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f5f5f5;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
}

/* Header */
.header {
  background-color: #007BFF;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}

.header h1 {
  font-size: 2.5rem;
}

.header p {
  margin-top: 10px;
  font-size: 1rem;
}

.navbar {
  margin-top: 20px;
}

.navbar a {
  color: #fff;
  text-decoration: none;
  margin: 0 10px;
}

.navbar a:hover {
  text-decoration: underline;
}

/* Main Content */
main {
  display: flex;
  margin: 20px 0;
}

.content {
  flex: 3;
  padding-right: 20px;
}

.content h2 {
  margin-bottom: 10px;
  font-size: 1.5rem;
  color: #007BFF;
}

.content p, .content ul {
  margin-bottom: 20px;
  line-height: 1.6;
}

.sidebar {
  flex: 1;
  background-color: #fff;
  padding: 20px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.sidebar .highlight h3 {
  font-size: 1.2rem;
  color: #007BFF;
}

.sidebar .cta-button {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #007BFF;
  color: #fff;
  text-align: center;
  text-decoration: none;
  border-radius: 5px;
}

.sidebar .cta-button:hover {
  background-color: #0056b3;
}

/* Footer */
.footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}

.footer-nav a {
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
}
