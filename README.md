<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>GAEUN'S IKEA MAGAZINE</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
        background-color: rgb(209, 137, 52);
        color: white;
      }

      .container {
        max-width: 800px;
        margin: 0 auto; 
        padding: 20px;
      }

      .magazine-page {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 50px;
      }

      .image-container {
        background-color: white;
        padding: 8px;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2); 
      }

      .magazine-page img {
        max-width: 100%;
        max-height: 500px;
        object-fit: contain;
      }

      .magazine-page h2 {
        margin-top: 20px;
        font-size: 24px;
        text-align: center;
      }

      .navigation-links a {
        color: white;
        text-decoration: none;
        padding: 10px 15px;
        border: 1px solid white;
        border-radius: 3px;
        font-size: 20px;
      }

      .navigation-links {
        justify-content: space-between;
        padding: 10px;
        border-radius: 5px;
        margin-top: 20px;
        text-align: center;
      }

      footer {
        text-align: center;
        padding: 20px;
      }
    </style>
  </head>

  <body>
    <div class="navigation-links">
      <a href="#1">HOME</a>
      <a href="#2">2</a>
      <a href="#3">3</a>
      <a href="#4">4</a>
    </div>

    <div class="container">
      <div class="magazine-page">
        <h1 style="font-size: 45px;">Which look could be the new you?</h1>
        <h2>Say hello to ÄNGSJÖN, HAVBÄCK and TÄNNFORSEN, three brand new bathroom furniture series - in three very different styles. Here you'll find fresh options for getting the look, functionality and convenience that best matches your taste and budget.</h2>
        <h2 style="font-size: 20px;">⬇ Keep scrolling to explore all bathroom series ⬇</h2>
      </div>

      <div class="magazine-page">
        <div class="image-container">
          <img src="https://i.imgur.com/QHg9HYF.png" alt="ÄNGSJÖN">
        </div>
        <h2>ÄNGSJÖN</h2>
      </div>

      <div class="magazine-page">
        <div class="image-container">
          <img src="https://i.imgur.com/2tNQ2gw.png" alt="HAVBÄCK">
        </div>
        <h2>HAVBÄCK</h2>
      </div>

      <div class="magazine-page">
        <div class="image-container">
          <img src="https://i.imgur.com/E1ZxYfn.png" alt="TÄNNFORSEN">
        </div>
        <h2>TÄNNFORSEN</h2>
      </div>

      <div class="magazine-page">
        <div class="image-container">
          <img src="https://i.imgur.com/3qJNraj.png" alt="ENHET and more">
        </div>
        <h2>ENHET and more</h2>
      </div>
    </div>

    <footer>
      &copy; 2024 IKEA Magazine
    </footer>
  </body>
</html>
