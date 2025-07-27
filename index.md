---
layout: single
author_profile: true
permalink: /
title: "Fouad Ibrahim Abdou Amir | Chercheur en Mathématiques Appliquées"
header:
  overlay_image: /images/headers/math-modeling.jpg  # .jpg en minuscules
  overlay_filter: 0.5
  caption: "Modélisation de systèmes dynamiques complexes"
excerpt: "Spécialiste des équations différentielles floues fractionnaires"
classes: wide
---

<style>
/* Solution définitive contre le chevauchement */
#main {
  position: relative;
  padding-left: 300px; /* Largeur sidebar */
}

/* Ajustements header */
.page__hero--overlay {
  width: calc(100% - 300px) !important;
  left: 300px !important;
  margin-top: 60px;
}

/* Adaptation mobile */
@media screen and (max-width: 1200px) {
  #main, .page__hero--overlay {
    padding-left: 0;
    left: 0;
    width: 100% !important;
  }
}

/* Cartes expertise */
.expertise-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 40px 0;
}
</style>

<div id="main">
  <div class="page__hero--overlay">
    <!-- Header content will go here automatically -->
  </div>

  <div class="custom-content">
    ## Domaines d'Expertise
    
    <div class="expertise-grid">
      <div class="expertise-card">
        <h3>Analyse Floue</h3>
        <ul>
          <li>Dérivées fractionnaires</li>
          <li>Théorie des semi-groupes</li>
        </ul>
      </div>
    </div>
    
    [Voir mon CV](/cv/){: .btn .btn--primary}
  </div>
</div>
