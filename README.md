<!DOCTYPE html>
<html>
  <head>
    <title>Feliz Aniversário Pedro!</title>
    <style>
      /* Defina a animação de piscar */
      @keyframes blink {
        0% { opacity: 1; }
        50% { opacity: 0; }
        100% { opacity: 1; }
      }
      
      /* Estilo do texto animado */
      .animated-text {
        font-size: 48px;
        font-weight: bold;
        color: red;
        animation: blink 1s infinite;
      }
      
      /* Estilo da imagem animada */
      .animated-image {
        width: 200px;
        height: 200px;
        animation: spin 2s linear infinite;
      }
      
      /* Defina a animação de girar */
      @keyframes spin {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
      }
    </style>
  </head>
  <body>
    <h1 class="animated-text">Feliz Aniversário Pedro!</h1>
    <img class="animated-image" src="https://images.app.goo.gl/piLPmjxDUqqgfXgp6" alt="Bolo de aniversário">
    <p>Parabéns pelo seu dia, Pedro!</p>
    <p>Que este novo ano seja repleto de saúde, felicidade e realizações!</p>
    <p><a href="link_de_acesso">Clique aqui para ver uma surpresa especial!</a></p>
  </body>
</html>

