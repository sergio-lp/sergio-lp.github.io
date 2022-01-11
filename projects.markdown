---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
title: Projetos
permalink: /projects/
feature_image: /assets/img/bg.jpg
feature_title: Projetos
feature_text: |
  # Projetos
---
<br/>
{% include projects.html %}


<!--<div class="card">
  <div class="card-container">
    <div class="project-title">
      <h4><b><a href="https://www.fcm.unicamp.br/adolescentes/">Adolescentes</a></b></h4>
    </div>
    {% include figure.html image="/assets/logo_original.png" width="225" %} <br /><br />

    <div id="myModal" class="modal">

      <span class="close">&times;</span>

      <div class="modal-content" id="img01">

        <div class="slideshow-container">

          <div class="mySlides fade">
            <div class="numbertext">1 / 4</div>
            <img src="/assets/img/adolescentes_1.png" style="width:100%">
          </div>

          <div class="mySlides fade">
            <div class="numbertext">2 / 4</div>
            <img src="/assets/img/adolescentes_2.png" style="width:100%">
          </div>

          <div class="mySlides fade">
            <div class="numbertext">3 / 4</div>
            <img src="/assets/img/adolescentes_3.png" style="width:100%">
          </div>

          <div class="mySlides fade">
            <div class="numbertext">4 / 4</div>
            <img src="/assets/img/adolescentes_4.png" style="width:100%">
          </div>

          <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
          <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
        <br>

        <div style="text-align:center">
          <span class="dot" onclick="currentSlide(1)"></span>
          <span class="dot" onclick="currentSlide(2)"></span>
          <span class="dot" onclick="currentSlide(3)"></span>
          <span class="dot" onclick="currentSlide(4)"></span>
        </div>

      </div>
    </div>

    <a href="https://www.fcm.unicamp.br/adolescentes/">Site</a> e <a href="https://play.google.com/store/apps/details?id=com.nrgbrainn.adolescentes">App</a> focados em medicina preventiva e promoção de saúde ao público adolescente.
    <br /><br />
    <a href="https://g1.globo.com/sp/campinas-regiao/noticia/2021/02/25/unicamp-lanca-aplicativo-e-site-para-explicar-temas-relacionados-a-saude-para-adolescentes.ghtml">G1 Campinas</a>
    |
    <a href="https://liberal.com.br/mais/bem-estar/unicamp-lanca-site-e-aplicativo-de-saude-adolescente-1468341/">O Liberal - Americana</a>
    |
    <a href="https://www.unicamp.br/unicamp/ju/noticias/2021/02/24/site-e-aplicativo-para-promocao-da-saude-de-adolescentes-sao-lancados-por">Unicamp</a>
    <br/>
    <a id="showImg">Imagens</a>
    <br /><br />

    <div class="chip">Material Design</div>
    <div class="chip">Kotlin</div>
    <div class="chip">Firebase</div>
  </div>
</div>

<div class="card">
  <div class="card-container">
    <div class="project-title">
      <h4><b>Track My Show</b></h4>
    </div>
    {% include figure.html image="/assets/bugdroid.png" width="125" %}

    A Simple Android app for getting information about your favorite movies and TV shows.<br />

    <div class="chip">Material Design</div>
    <div class="chip">Java</div>
    <div class="chip">TMDb API</div>
    <div class="chip">REST</div>
  </div>
</div>

<script>
  // Get the modal
  var modal = document.getElementById("myModal");

  // Get the image and insert it inside the modal - use its "alt" text as a caption
  var img = document.getElementById("showImg");
  var modalImg = document.getElementById("img01");
  var captionText = document.getElementById("caption");
  img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
  }

  // Get the <span> element that closes the modal
  var span = document.getElementsByClassName("close")[0];

  // When the user clicks on <span> (x), close the modal
  span.onclick = function() {
    modal.style.display = "none";
  }

  var slideIndex = 1;
  showSlides(slideIndex);

  // Next/previous controls
  function plusSlides(n) {
    showSlides(slideIndex += n);
  }

  // Thumbnail image controls
  function currentSlide(n) {
    showSlides(slideIndex = n);
  }

  function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    if (n > slides.length) {
      slideIndex = 1
    }
    if (n < 1) {
      slideIndex = slides.length
    }
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex - 1].style.display = "block";
    dots[slideIndex - 1].className += " active";
  }
</script>-->
