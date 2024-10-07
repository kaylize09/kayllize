html lang="pt.br">

<body>
    <link rel="stylesheet" href="styles.css" />
    <title>STYLEEFLIX</title><link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Protest+Guerrilla&display=swap" rel="stylesheet">
    <header>STYLEEFLIX</header>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>Meu Demônio Favorito </h1>
            <p>#meu-demônio-favorito</p>
        </div>


        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/ZZ-tK8948H4?si=0k-hawsj-xvftjQr"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>
 
    <section class="categoria">
       <h2>filmes e séries</h2>
       <div class="categoria-videos">
        <img src="https://img.youtube.com/vi/Fv204VxyMA8/maxresdefault.jpg" />
        <img src="https://img.youtube.com/vi/7OOLoKL5qD8/maxresdefault.jpg">
        <img src="https://img.youtube.com/vi/KOh5B5R033E/maxresdefault.jpg">
        <img src="https://img.youtube.com/vi/1K2g647oB-c/maxresdefault.jpg">
        <img src="https://img.youtube.com/vi/gE36GXSY6o4/maxresdefault.jpg">
    </div>
    </section>
</body>



</html>



body{
  color:beige;
  background:#030003ea;
  margin: 0px; 
  font-family: "Chakra Petch", sans-serif;
}

header{
  border-bottom: solid 2px rgba(242, 236, 236, 0.974);
  padding : 20px ;
  font-size: 29px;
}



/* código omitido */

.chamada {
  background: rgba(151, 4, 4, 0.974)
  padding-box: 80px;
  padding-top: 80px;
  display: flex;
  justify-content: center;
}

.chamada-texto {
  margin-right: 5%;
}

h1 {
font-size: 35px;
}


p {
  font-size: 20px;
}

.categoria-videos {
display: flex;
overflow-x: auto;
gap: 10px;
}

.categoria {
padding-left: 20px;
padding-right: 20px;
}

.categoria-videos img {

  opacity: 0,5;
}

.categoria-videos img:hover {

  opacity: 1.0;
  border: 1px;  solid white;
}

.categoria h2 {
  color:rgb(240, 240, 241)
}
