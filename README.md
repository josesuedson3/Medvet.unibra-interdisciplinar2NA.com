<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adote com Amor</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      background: #101010;
      color: #f4f4f4;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://cdn.pixabay.com/photo/2016/11/29/09/13/dog-1861839_1280.jpg') no-repeat center center/cover;
      height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 15px;
    }
    header p {
      font-size: 1rem;
      color: #ffd700;
    }
    nav {
      background: #1a1a1a;
      display: flex;
      justify-content: center;
      padding: 12px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: #f4f4f4;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      position: relative;
    }
    nav a::after {
      content: '';
      display: block;
      height: 2px;
      background: #ffd700;
      transition: width 0.3s;
      width: 0;
      margin-top: 5px;
    }
    nav a:hover::after {
      width: 100%;
    }
    section {
      max-width: 960px;
      margin: 40px auto;
      padding: 25px;
      background: #1e1e1e;
      border-radius: 10px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.3);
      transition: all 0.3s ease-in-out;
    }
    section h2 {
      color: #ffd700;
      margin-bottom: 20px;
    }
    ul {
      padding-left: 20px;
    }
    ul li {
      margin-bottom: 10px;
    }
    footer {
      background: #000;
      color: #ccc;
      text-align: center;
      padding: 20px 10px;
      margin-top: 40px;
    }
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }
      nav a {
        margin: 0 8px;
        font-size: 0.85rem;
      }
      section {
        margin: 20px 10px;
        padding: 20px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Adote com Amor</h1>
    <p>Médica Veterinária • Não abandone os animais. Eles têm coração!</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#maus-tratos">Maus-Tratos</a>
    <a href="#como-ajudar">Como Ajudar</a>
    <a href="#voluntariado">Voluntariado</a>
  </nav>

  <section id="sobre">
    <h2>Sobre o Nosso Projeto</h2>
    <p>Nosso projeto tem como objetivo principal a conscientização da sociedade sobre os impactos do abandono e maus-tratos aos animais. Lutamos para oferecer suporte, incentivar a adoção responsável e criar um ambiente mais seguro e acolhedor para todos os animais em situação de rua. Acreditamos que, com empatia, informação e ação, podemos transformar vidas e garantir dignidade a esses seres indefesos.</p>
  </section>

  <section id="maus-tratos">
    <h2>Maus-Tratos e Abandono</h2>
    <p><strong>Maus-Tratos aos Animais:</strong> Agressões, negligência, fome, falta de abrigo ou cuidados veterinários são crimes e causam traumas graves.</p>
    <p><strong>Abandono de Animais:</strong> É desumano, causa sofrimento e é crime segundo a Lei nº 9.605/98.</p>
  </section>

  <section id="dificuldades">
    <h2>Dificuldades e Solidariedade</h2>
    <p><strong>Quando Falta Dinheiro, Mas Sobra Amor:</strong> Nem todo abandono vem da maldade. Às vezes é o desespero. Nosso projeto conecta quem precisa de ajuda com quem pode ajudar, incentivando campanhas e ações comunitárias.</p>
  </section>

  <section id="bem-estar">
    <h2>Bem-Estar Animal</h2>
    <p>O bem-estar animal é um princípio fundamental que garante que os animais vivam em condições adequadas, com liberdade de se alimentar, se abrigar, expressar seus comportamentos naturais e receber cuidados veterinários. Promover o bem-estar é mais do que evitar sofrimento - é garantir qualidade de vida, respeito e dignidade a todos os seres vivos.</p>
    <p>Nosso projeto também defende ações educativas e políticas públicas que incentivem a guarda responsável, a proteção animal e o acesso a serviços básicos para tutores de baixa renda.</p>
  </section>

  <section id="como-ajudar">
    <h2>Como Ajudar</h2>
    <ul>
      <li>Adote com responsabilidade</li>
      <li>Denuncie maus-tratos</li>
      <li>Doe ração, cobertores, medicamentos, etc.</li>
      <li>Divulgue nas redes sociais</li>
      <li>Apoie ONGs e abrigos locais</li>
    </ul>
  </section>

  <section id="voluntariado">
    <h2>Voluntariado e Doações</h2>
    <p><strong>Seja Voluntário:</strong> Ajude em feiras de adoção, no cuidado diário, transporte ou divulgação.</p>
    <p><strong>Faça Doações:</strong> Toda ajuda conta! Doe alimentos, dinheiro, tempo e carinho.</p>
  </section>

  <section id="integrantes" style="font-size: 0.9rem; text-align: center;">
  <h2 style="color: #ffd700; font-size: 1.5rem;">Integrantes do Projeto:</h2>
  <ul style="list-style: none; padding: 0; column-count: 2; column-gap: 40px; max-width: 600px; margin: auto;">
    <li>Ana Beatriz</li>
    <li>Claudia Price</li>
    <li>Diana Barbosa</li>
    <li>Emanuel Lucas</li>
    <li>Ewele Maria Sena da Silva</li>
    <li>Heitor José Barbosa Muniz</li>
    <li>Jailson Barbosa</li>
    <li>José Suedson</li>
    <li>Maria Luiza</li>
    <li>Raíssa Vitória</li>
    <li>Rodrigo Lemos</li>
  </ul>
  <h3 style="margin-top: 20px; color: #ffd700;">Feito por:</h3>
  <p style="font-size: 0.9rem;">Suedson (site)<br>José Suedson Fonseca do Nascimento</p>
</section>

  <p style="color: #ffd700; font-weight: bold; font-size: 1rem; text-align: center;">© 2025 Adote com Amor, Desenvolvido por Suedson.</p>
  </footer>
</body>
</html>
