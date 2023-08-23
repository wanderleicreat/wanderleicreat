- 👋
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="assets/images/futebol.png">
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="assets/css/estilo.css">
    <title>Modaly-Sorteios</title>
</head>
<body>
 <div vw class="enabled">
    <div vw-access-button class="active"></div>
    <div vw-plugin-wrapper>
      <div class="vw-plugin-top-wrapper"></div>
    </div>
  </div>
  <script src="https://vlibras.gov.br/app/vlibras-plugin.js"></script>
  <script>
    new window.VLibras.Widget('https://vlibras.gov.br/app');
  </script>
    <div class="container">
        <header>
            <input type="checkbox" id="menu">
                    <label class="menu" for="menu"><i class="fa fa-navicon" style="font-size:36px"></i>
            </label>
            <div class="img-menu">
             
            </div>
            <div class="nav">
                <ul class="nav-list">
                    <li class="nav-item"><a href="index.html">Home</a></li> 
                    <li class="nav-item"><a href="jogadores.html">Jogadores</a></li>
                    <li class="nav-item"><a href="cronometro.html">Cronômetro</a></li>
                </ul> 
            </div>
        </header> <!-- FIM HEADER -->

        <section>
            <div class="titulo">
                <h1>Bem vindo(a) ao Modaly-Sorteios!</h1>
                <h1>Vamos começar</h1>
            </div>
            <div class="conteudo-home">
                <a href="index.html">
                    <div class="card">
                        <div class="titulo-card">
                            <h1>Olá craque!</h1>
                        </div>
                        <div class="descricao-card">
                            <h3>Somos um sistema especializado em sortear times para sua pelada.</h3>
                            <h3>Apenas informe quem são os jogadores e o resto é por nossa conta!</h3>
                            <img src="assets/images/bola.png" alt="uma bola que foi chutada,com as cores branca,azul e amarela"> 
                        </div>
                </a>
                </div>

                <a href="jogadores.html">
                    <div class="card">
                        <div class="titulo-card">
                            <h1>Jogadores</h1>
                        </div>
                        <div class="descricao-card">
                            <h3>Existe futebol sem jogadores?</h3>
                            <h3>Então clique aqui e adicione novos players para a sua pelada!</h3>
                            <img src="assets/images/jogador.png" alt="uma pessoa com as roupas das cores do brasil,azul e amarelo,chutando uma bola branca ">
                        </div>
                    </a>
                </div>

                <a href="cronometro.html">
                    <div class="card">
                        <div class="titulo-card">
                            <h1>Cronômetro</h1>
                        </div>
                        <div class="descricao-card">
                            <h3>Quer ter um árbitro online?</h3>
                            <h3>Então clique aqui e defina o tempo da sua partida!</h3>
                            <img src="assets/images/cronometro.png" alt="uma mão segundo o crônometro e contar o tempo do começo ao fim" >
                        </div>
                    </a>
                </div>
            </div>
        </section>

    <script src="script.js"></script>
</body>
</html>
