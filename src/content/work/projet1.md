---
title: Renforcer la citoyenneté de notre association Offrir des bases solides et un avenir prometteur.
publishDate: 2025-01-10 00:00:00
img: /assets/donneko.jpg
img_alt: voir enfants
description: |
  Eliora Association est au service des enfants orphelins et de leurs proches, en respectant leurs droits et nos valeurs fondatrices : le respect, l’amour, l’éducation. Notre mission est de faire au mieux ce que nous faisons déjà et de rester constamment à l’écoute pour le bien-être des enfants et des personnes qui nous font confiance
tags:
  - Amour et Respect
  - Esprit d’équipe
---
<script>
    function openInSameTab(url) {
        window.location.href = url;
    }
</script>



## Notre Projet Associatif 2025 – 2028

Pour les prochaines années, nous avons défini trois priorités :
	1.	Renforcer la citoyenneté de notre association : Offrir des bases solides et un avenir prometteur.
	2.	Développer une offre de services : Une agriculture plus inclusive pour mieux accueillir, accompagner et prendre soin des enfants.
	3.	Construire un grand orphelinat au Congo : La Maison d’Accueil Eliora, sur un terrain que nous possédons déjà.

Je vous invite à découvrir l’ONG Eliora, à nous contacter et à nous rejoindre, car c’est ensemble que nous pourrons œuvrer pour le bien-être des enfants :

	« Seul on va plus vite, ensemble nous allons plus loin. »

  <section class="carousel">

  <div class="carousel-inner">
        <img src="/assets/ye.jpg" alt="Image 1">
        <img src="/assets/princess.jpg" alt="Image 2">
        <img src="/assets/viito.jpg" alt="Image 3">
        <img src="/assets/orphe.jpg" alt="Image 4">
        <!-- Ajoute autant d'images que tu veux -->
    </div>
    <button class="prev" onclick="plusSlides(-1)">&#10094;</button>
    <button class="next" onclick="plusSlides(1)">&#10095;</button>

<style>
    .carousel {
    position: relative;
    max-width: 100%;
    margin: auto;
    overflow: hidden;
}

.carousel-inner {
    display: flex;
    transition: transform 0.5s ease;
}

.carousel-inner img {
    width: 100%;
    height: auto;
    display: none; /* Pour cacher les images sauf la première */
}

.carousel-inner img:first-child {
    display: block; /* Afficher la première image par défaut */
}

.prev, .next {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    border: none;
    cursor: pointer;
    padding: 10px;
}

.prev {
    left: 10px;
}

.next {
    right: 10px;
}

</style>

<script>
let slideIndex = 0;
showSlides(slideIndex);

// Fonction pour passer à la slide suivante automatiquement toutes les 3 secondes (3000 ms)
setInterval(() => {
    plusSlides(1);
}, 3000);

function plusSlides(n) {
    showSlides(slideIndex += n);
}

function showSlides(n) {
    let slides = document.querySelectorAll('.carousel-inner img');
    if (n >= slides.length) { slideIndex = 0 }
    if (n < 0) { slideIndex = slides.length - 1 }
    slides.forEach((slide, index) => {
        slide.style.display = (index === slideIndex) ? 'block' : 'none';
    });
}

</script>
</section>