<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rucoy Boss Tracker</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #ffffff;
      margin: 0;
      padding: 20px;
    }
    header {
      text-align: center;
      margin-bottom: 40px;
    }
    h1 {
      color: #4caf50;
    }
    .boss-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .boss-card {
      background-color: #1e1e1e;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }
    .boss-card h2 {
      margin: 0 0 10px;
      color: #f44336;
    }
    .boss-card p {
      margin: 5px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Rucoy Online - Boss Tracker</h1>
    <p>Descubra em qual servidor tem Boss ativo e qual o tipo de Boss</p>
  </header>

  <section class="boss-list" id="bossList">
    <!-- Bosses aparecerão aqui -->
    <div class="boss-card">
      <h2>Red Dragon</h2>
      <p><strong>Servidor:</strong> BR-5</p>
      <p><strong>Local:</strong> Dungeon Sul</p>
      <p><strong>Status:</strong> Ativo</p>
    </div>
    <div class="boss-card">
      <h2>Ice Demon</h2>
      <p><strong>Servidor:</strong> EU-2</p>
      <p><strong>Local:</strong> Caverna Congelada</p>
      <p><strong>Status:</strong> Ativo</p>
    </div>
  </section>
</body>
</html>
