.about-title {
  
  text-align: center;
  font-size: 2.3rem;
  font-weight: 600;
  margin-bottom: 50px;
  color: #1a1a1a;
}

.about-container {
  margin: 50px;
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  align-items: center;
  justify-content: center;
}

.about-text {
  flex: 1 1 500px;
  font-size: 1.05rem;
  line-height: 1.8;
}

.about-subtitle {
  font-size: 1.5rem;
  font-weight: 500;
  color: #222;
  margin-bottom: 20px;
}

.about-quote {
  margin-top: 25px;
  font-style: italic;
  color: #666;
  border-left: 4px solid #888;
  padding-left: 15px;
}

.about-image {
  flex: 1 1 350px;
  text-align: center;
}

.about-image img {
  width: 100%;
  max-width: 340px;
  height: auto;
  border-radius: 20px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/*legenda*/
.image-caption {
  margin-top: 15px;
}

.image-caption h4 {
  font-size: 1.2rem;
  font-weight: 600;
  color: #1a1a1a;
}

.image-caption p {
  font-size: 0.95rem;
  color: #777;
}

/* cards sobre a PF (semana.html)*/
.timeline-section {
  max-width: 10000px;
  margin: 20px;
  padding: 50px;
  font-family: "Poppins", sans-serif;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 30px;
}

.timeline-card {
  flex: 1 1 30%;
  background: #f7f5f4;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}


.card-content h3 {
  font-size: 1.3rem;
  font-weight: 600;
  color: #222;
  margin-bottom: 10px;
}

.card-content p {
  font-size: 1rem;
  color: #555;
  line-height: 1.6;
  margin-bottom: 15px;
}

.obs {
  font-size: 0.95rem;
  background: #fff;
  border-left: 4px solid #8c1414;
  padding: 8px 10px;
  border-radius: 6px;
  color: #444;
}

.botao-sobre {
  text-align: center;
}

.sobre-link {
  display: inline-block;
  padding: 10px 22px;
  background: #8c1414;
  color: #fff;
  font-weight: 600;
  border-radius: 25px;
  text-decoration: none;
  transition: 0.3s;
}






<section class="timeline-section">
  <div class="timeline-line"></div>

  
  <div class="timeline-card left">
    <div class="card-content">
      <h3>Intercurso 🧩</h3>
      <p>
        Evento anual onde cada curso é um time, promovendo a integração entre alunos principalmente do mesmo curso, mas também entre todos os participantes.
       A competição e torcida promovem uma atmosfera animadora para todos os participantes. E assim com a ajuda individual de cada aluno de um determinado curso para contribuir na pontuação e apoiar nas competições coletivas e individuais traz a unidade esperada na competição. 
      </p>
      <div class="obs">
        <strong>Obs:</strong>A competição engloba atividades culturais, esportivas e sociais.
      </div>
    </div>
  </div>


  <div class="timeline-card right">
    <div class="card-content">
      <h3>Esportes ⚽</h3>
      <p>
        O incentivo a práticas esportivas é um forma de promover saúde, espírito esportivo,
        trabalho em equipe e uma competição saudável entre os estudantes. 
        Além de que na competição não tem apenas esportes tradicionais, mas também brincadeiras, jogos, games online, e diversas coisas, dessa forma é mais fácil atingir todos os públicos para participação, cada brincadeira, contém uma pontuação diferente, onde o primeiro, segundo, terceiro e quarto lugar também variam entre si. 
      
      </p>
      <div class="obs">   
        <strong>Obs:</strong>A pontuação varia de cada esporte para saber mais clique no botão abaixo.
      </div>
      <br>
      <br>
      <div class="botao-sobre">
        <a href="moda.html" class="sobre-link">Saiba mais</a>
      </div>
    </div>
  </div>

  <div class="timeline-card left">
    <div class="card-content">
      <h3>Doações 🎁</h3>
      <p>
        As doações tem o objetivo de arrecadar roupas, alimentos, produtos de higiene, lacres, tampinhas, livros e etc. para contribuir para comunidades carentes da região. 
        Também equivalendo a pontos para a equipe, ou seja, dessa forma o incentivo a doação vai além da causa, trata-se de competição e caridade.
        Os produtos doados tem diferentes pontuações, porém elementos como brinquedos, roupas, sapatos, livros e etc. são variáveis, com um mínimo e máximo valor de pontos estipulado, por exemplo, brinquedos valem de 5 a 20 pts.
      </p>
      <div class="obs">
        <strong>Obs:</strong>Para saber mais sobre as doações e pontuações clique no botão abaixo.
      </div>
        <br>
      <div class="botao-sobre">
        <a href="doa.html" class="sobre-link">Saiba mais</a>
      </div>
    </div>
  </div>
</section>
