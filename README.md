<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thiago Pongelupe Buffet e Consultoria</title>
  <style>
    /* Estilo Básico */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #333;
      color: #fff;
      padding: 10px 20px;
    }
    header a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
    }
    .hero {
      text-align: center;
      color: #fff;
      background: url('churrasco.jpg') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .hero h1 {
      font-size: 3rem;
      margin: 0;
    }
    .hero p {
      font-size: 1.5rem;
    }
    .hero button {
      margin-top: 20px;
      padding: 10px 20px;
      font-size: 1rem;
      background-color: #ff6600;
      border: none;
      color: #fff;
      cursor: pointer;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    section h2 {
      margin-bottom: 20px;
      font-size: 2rem;
    }
    .cards {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .card {
      border: 1px solid #ddd;
      padding: 20px;
      width: 300px;
      text-align: left;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #ff6600;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <div>Thiago Pongelupe</div>
    <nav>
      <a href="#about">Sobre Nós</a>
      <a href="#services">Serviços</a>
      <a href="#testimonials">Depoimentos</a>
      <a href="#contact">Contato</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Transforme seu evento ou negócio de churrasco</h1>
    <p>Excelência, segurança e qualidade garantidas</p>
    <button>Saiba Mais</button>
  </div>

  <section id="about">
    <h2>Sobre Nós</h2>
    <p>Com anos de experiência, transformamos sonhos em realidade com soluções personalizadas para negócios e eventos.</p>
  </section>

  <section id="services">
    <h2>Nossos Serviços</h2>
    <div class="cards">
      <div class="card">
        <h3>Consultoria Especializada</h3>
        <p>Planejamento estratégico para churrascarias.</p>
      </div>
      <div class="card">
        <h3>Buffet Premium</h3>
        <p>Experiência gastronômica completa para eventos.</p>
      </div>
      <div class="card">
        <h3>Mentoria Personalizada</h3>
        <p>Suporte contínuo para crescimento do negócio.</p>
      </div>
    </div>
  </section>

  <section id="testimonials">
    <h2>Depoimentos</h2>
    <p>"Nossa churrascaria aumentou as vendas em 40%. Excelente consultoria!" - João Silva</p>
  </section>

  <section id="contact">
    <h2>Entre em Contato</h2>
    <form>
      <input type="text" placeholder="Seu Nome" required><br><br>
      <input type="email" placeholder="Seu E-mail" required><br><br>
      <textarea placeholder="Sua Mensagem"></textarea><br><br>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>© 2024 Thiago Pongelupe Buffet e Consultoria. Todos os direitos reservados.</p>
    <p><a href="#">Política de Privacidade</a></p>
  </footer>
</body>
</html>
