<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Café Berlin</title>

  <style>
    body {
      margin: 0;
      font-family: "Arial", sans-serif;
      color: #2b2b2b;
      background: #f7f3ee;
    }

    header {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                  url('https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=1500&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-size: 60px;
      margin: 0;
    }

    header p {
      font-size: 20px;
      margin-top: 10px;
    }

    .button {
      margin-top: 25px;
      padding: 12px 24px;
      background: #c59d5f;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      transition: 0.3s;
    }

    .button:hover {
      background: #a87f45;
    }

    section {
      max-width: 900px;
      margin: auto;
      padding: 80px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 32px;
      margin-bottom: 20px;
    }

    .features {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 40px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      width: 250px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
    }

    footer {
      background: #2b2b2b;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>

<body>

<header>
  <h1>Café Berlin</h1>
  <p>Der beste Kaffee in der Stadt</p>
  <a href="#contact" class="button">Besuch uns</a>
</header>

<section>
  <h2>Über uns</h2>
  <p>
    Wir sind ein gemütliches Café im Herzen der Stadt. 
    Frischer Kaffee, hausgemachte Kuchen und eine warme Atmosphäre. alles für dein lächel
  </p>

  <div class="features">
    <div class="card">
      <h3>☕ Kaffee</h3>
      <p>Frisch geröstete Bohnen täglich.</p>
    </div>

    <div class="card">
      <h3>🍰 Kuchen</h3>
      <p>Hausgemachte Kuchen und Desserts.</p>
    </div>

    <div class="card">
      <h3>📍 Lage</h3>
      <p>Zentral in Berlin, leicht erreichbar.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Kontakt</h2>
  <p>Besuche uns oder schreibe uns eine Nachricht.</p>
  <p><strong>Email:</strong> cafe@berlin.de</p>
</section>

<footer>
  <p>© 2026 Café Berlin</p>
</footer>

</body>
</html>
