<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Estilo Mercado Livre</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    :root {
      --ml-yellow: #ffe600;
      --ml-blue: #3483fa;
      --ml-dark-gray: #333333;
      --ml-light-gray: #999999;
      --ml-background: #f5f5f5;
      --ml-white: #ffffff;
      --ml-border: #e6e6e6;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background-color: var(--ml-background);
      color: var(--ml-dark-gray);
    }

    .header {
      background-color: var(--ml-yellow);
      padding: 16px 24px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .search-bar {
      width: 100%;
      max-width: 600px;
      padding: 10px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
    }

    .main {
      padding: 24px;
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 16px;
    }

    .card {
      background-color: var(--ml-white);
      border: 1px solid var(--ml-border);
      border-radius: 8px;
      padding: 16px;
      transition: box-shadow 0.2s ease;
    }

    .card:hover {
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    .card img {
      width: 100%;
      height: auto;
      border-radius: 4px;
      margin-bottom: 12px;
    }

    .title {
      font-size: 1rem;
      margin-bottom: 8px;
    }

    .price {
      font-size: 1.25rem;
      font-weight: bold;
    }

    .button-primary {
      background-color: var(--ml-blue);
      color: var(--ml-white);
      border: none;
      padding: 10px 16px;
      border-radius: 4px;
      cursor: pointer;
      margin-top: 12px;
      width: 100%;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header class="header">
    <input type="text" class="search-bar" placeholder="Buscar produtos, marcas e muito mais..." />
  </header>

  <main class="main">
    <div class="card">
      <img src="https://via.placeholder.com/250x150" alt="Produto 1">
      <div class="title">Produto Exemplo 1</div>
      <div class="price">R$ 199,90</div>
      <button class="button-primary">Comprar</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/250x150" alt="Produto 2">
      <div class="title">Produto Exemplo 2</div>
      <div class="price">R$ 349,90</div>
    a href="http://mpago.la/1dotChm" target="_blank" style="padding: 10px 20px; background-color: #28a745; color: white; border: none; border-radius: 5px; text-decoration: none; font-size: 16px;">
  Pagar agora
</a>
    </div>
  </main>
</body>
</html>
