<!DOCTYPE html>
<html lang"pt-br>
    <head>
        <meta charset="UTF-8"/>
        <title>Segundo Projeto Over Glass</title>
        <link rel="stylesheet" href="_css/estilo.css">
        <style>

video#filme {
    display: block;
    position: relative;
    left: 85px;
    top: -20px;

}

video#filme2 {
    display: block;
    position: relative;
    left: 5px;
    width: 350px;

}
        </style>


    </head>
<script lang="javascrpith" src="_javascript/funcoes.js"></script>    
<body>

    <div id="interface">  

        <header id="cabecalho">
        <hgroup>
        <h1>Google Glass</h1>
        <h2>A revolução do Google está chegando</h2>
        </hgroup>

        <img id="icone" src="_imagens/glass-oculos-preto-peq.png"/>

        <nav id="menu">
        <h1>Menu Principal</h1>
        <ul>
          <li onmouseover="mudaFoto('_imagens/home.png')" onmouseout="mudaFoto('_imagens/glass-oculos-preto-peq.png')"><a href="index.html">Home</li></a>
          <li onmouseover="mudaFoto('_imagens/especificacoes.png')" onmouseout="mudaFoto('_imagens/glass-oculos-preto-peq.png')"><a href="specs.html">Especificações</li></a>
          <li onmouseover="mudaFoto('_imagens/fotos.png')" onmouseout="mudaFoto('_imagens/glass-oculos-preto-peq.png')"><a href="fotos.html">Fotos</li></a>
          <li onmouseover="mudaFoto('_imagens/multimidia.png')" onmouseout="mudaFoto('_imagens/glass-oculos-preto-peq.png')"><a href="multimidia.html">Multimídia</li></a>
          <li onmouseover="mudaFoto('_imagens/contato.png')" onmouseout="mudaFoto('_imagens/glass-oculos-preto-peq.png')"><a href="fale-conosco.html">Fale Conosco</li></a>
        </ul>
        </nav>
         </header>

<section id="corpo">        
<article id="noticia-principal">
    <header id="cabecalho-artigo">
    <hgroup>
     <h2>Tecnologia > Inovações</h2>
     <h1>Saiba tudo sobre o Google Glass</h1>
     <h3>por desenvolvedor <br>em 01/Ago/2022</h3>
    </hgroup>
    </header>

<h2>O que é</h2>
<p>O <span style="text-decoration: underline;">Google Glass</span> é um acessório em forma de óculos que possibilita a interação dos usuários com diversos conteúdos em realidade aumentada. Também chamado de Project Glass, o eletrônico é capaz de tirar fotos a partir de comandos de voz, enviar mensagens instantâneas e realizar vídeoconferências. Seu lançamento está previsto para 2014, e seu preço deve ser de US$ 1,5 mil. Atualmente o <a href="http://glass.google.com" target="_blank">Google Glass</a> encontra-se em fase de testes e já possui um vídeo totalmente gravado com o dispositivo. Além disso, a companhia de buscas registrou novas patentes anti-furto e de desbloqueio de tela para o acessório.</p>

<figure class="foto-legenda">
 <img src="_imagens/glass-quadro-homem-mulher.jpg"/>
<figcaption>
    <h2>Primeiro trabalho</h2>
    <p>Como esta sendo o projeto do meu primeiro site</p>
</figcaption>

</figure>
<h2>Data de lançamento</h2>
<p>Não há uma data específica e oficial para o dispositivo ser lançado, ainda. Pode ser que ele esteja disponível em demonstrações a partir de 2013, mas seu lançamento para as lojas fica para, pelo menos, 2014.</p>

<h2>Especificações Técnicas</h2>
<table id="tabelaspec">
<caption>Técnica do Google Glass <span>Ago/2022</span> </caption>

<tr><td class="ce">Tela</td><td class="cd">Resolução equivalente a tela de 25"</td></tr>
<tr><td rowspan="2" class="ce">Camera</td> <td class="cd">5MP para fotos</td></tr>
<tr><td class="cd">720p para vídeos</tr></td>
<tr><td rowspan="2" class="ce">Conectividade</td> <td class="cd"> Wi-Fi</td></tr>
<tr><td class="cd">Bluetooth</tr></td>
<tr><td class="ce">Memória Interna</td> <td class="cd">12GB</td></tr>
</table>

<h2>Como funciona</h2>
<p>De acordo com fontes próximas do Google, os óculos vão contar com uma pequena tela de LCD ou AMOLED na parte superior e em frente aos olhos do usuário. Com o uso de uma câmera e GPS, você pode se situar, assim como selecionar opções com o movimento da cabeça</p>

<h2>O que você pode fazer com o Google Glasses</h2>
<p>O vídeo de divulgação do Google mostra que você pode se transformar em uma espécie de “super<wbr/>-humano”, já que o aparelho pode indicar a quantos metros você está de seu destino, se o metrô está aberto ou fechado, mostrar o clima, agenda e até mesmo permitir que você marque encontros apenas com comandos de voz.</p>
</article>

<div id="tv-radio"> 
    <video id="filme" controls="contrls" poster="_imagens/video-mini02.jpg">
        <source src="_media/how-it-feels.mp4" type="video/mp4"/>
        Desculpe, mas não foi possivel carregar o Vídeo.

    </video>


</div>

</section>
<aside id="lateral">
<h1>Outras noticiais</h1>
<h2> Video mais recente</h2>
<div id="tv-radio">    
    <video id="filme2" controls="contrls" poster="_imagens/video-mini01.jpg">
        <source src="_media/one-day.mp4" type="video/mp4"/>
        Desculpe, mas não foi possivel carregar o Vídeo.

    </video>


</div>
<h3>Novidades no Glass</h3>
<p>O Google enfim revelou as especificações completas do Google Glass, e com ele uma surpresa ainda inédita no mercado: a gigante das buscas usará um sistema de áudio baseado na transdução por condução. Através das hastes dos óculos, o som será transmitido para o ouvido do usuário por meio de microvibrações em determinados ossos de sua cabeça, sem usar nenhum tipo de alto-falante.

Além da surpresa do áudio, a tela montada a frente do olho do usuário também chamou atenção. Serão 640 x 360 pixels de resolução que, em proporção, equivaleria a um monitor de 25 polegadas de alta definição colocado a 2,5 metros de distância do espectador.</p>
</aside>
<footer id="rodape"> 
<p>Copyright &copy; 2022 - by Guilherme Almeida <br><a href="http://linkedin.com/in/guilherme-almeida-553957244" target="_blank">Desenvolvedor</a></p>
</footer>
</div>  
</body>
</html>