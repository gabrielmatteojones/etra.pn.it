---
layout: default              # Specifica il layout da usare (es. _layouts/default.html)
title: Organizzazioni Jonez  # Titolo della pagina
description: Questo è un esempio di homepage con utilizzo del componente "hero"  # Meta description (utile per SEO)
lang: it                     # Lingua della pagina
permalink: /orgs/            # URL finale della pagina
order: 1                     # (Opzionale) Ordine per la navigazione o elenchi
---

<div class="container">

<link rel="stylesheet" href="https://designsystem.digital.gov/assets/styles.css">
-->
<section aria-labelledby="progetti-heading" class="usa-section">
  <div class="grid-container">
    <h2 id="progetti-heading" class="usa-heading">I miei progetti</h2>
    <!-- Grid: 3 colonne su desktop, 1 su mobile -->
    <div class="grid-row grid-gap">
      <!-- Card 1 -->
      <div class="grid-col-12 tablet:grid-col-6 desktop:grid-col-4">
        <article class="usa-card" aria-labelledby="proj1-title">
          <div class="usa-card__container">
            <!-- immagine / visuale -->
            <div class="usa-card__img" role="img" aria-label="Screenshot progetto Alpha" style="background: #e6eef8; height: 160px; display:flex; align-items:center; justify-content:center;">
              <span class="usa-sr-only">Immagine progetto Alpha</span>
              <!-- Inserisci <img src="..." alt=""> se preferisci -->
              <svg width="64" height="64" aria-hidden="true" focusable="false"><rect width="64" height="64" fill="#cfe0f7"/></svg>
            </div>
            <header class="usa-card__header">
              <h3 class="usa-card__heading" id="proj1-title">Progetto Alpha</h3>
            </header>
            <div class="usa-card__body">
              <p class="margin-top-0">Breve descrizione del progetto Alpha: obiettivi, tecnologie usate e risultato principale raggiunto.</p>
            </div>
            <footer class="usa-card__footer">
              <a class="usa-button usa-button--unstyled" href="#" aria-label="Vai ai dettagli di Progetto Alpha">Dettagli →</a>
            </footer>
          </div>
        </article>
      </div>
      <!-- Card 2 -->
      <div class="grid-col-12 tablet:grid-col-6 desktop:grid-col-4">
        <article class="usa-card" aria-labelledby="proj2-title">
          <div class="usa-card__container">
            <div class="usa-card__img" role="img" aria-label="Screenshot progetto Beta" style="background: #f3efe6; height: 160px; display:flex; align-items:center; justify-content:center;">
              <span class="usa-sr-only">Immagine progetto Beta</span>
              <svg width="64" height="64" aria-hidden="true" focusable="false"><rect width="64" height="64" fill="#efe0cfe"/></svg>
            </div>
            <header class="usa-card__header">
              <h3 class="usa-card__heading" id="proj2-title">Progetto Beta</h3>
            </header>
            <div class="usa-card__body">
              <p class="margin-top-0">Breve descrizione del progetto Beta: ruolo svolto, sfide affrontate e benefici per gli utenti.</p>
            </div>
            <footer class="usa-card__footer">
              <a class="usa-button usa-button--unstyled" href="#" aria-label="Vai ai dettagli di Progetto Beta">Dettagli →</a>
            </footer>
          </div>
        </article>
      </div>
      <!-- Card 3 -->
      <div class="grid-col-12 tablet:grid-col-6 desktop:grid-col-4">
        <article class="usa-card" aria-labelledby="proj3-title">
          <div class="usa-card__container">
            <div class="usa-card__img" role="img" aria-label="Screenshot progetto Gamma" style="background: #eef8f0; height: 160px; display:flex; align-items:center; justify-content:center;">
              <span class="usa-sr-only">Immagine progetto Gamma</span>
              <svg width="64" height="64" aria-hidden="true" focusable="false"><rect width="64" height="64" fill="#dff3e6"/></svg>
            </div>
            <header class="usa-card__header">
              <h3 class="usa-card__heading" id="proj3-title">Progetto Gamma</h3>
            </header>
            <div class="usa-card__body">
              <p class="margin-top-0">Breve descrizione del progetto Gamma: impatto misurabile, metriche e prossimi passi.</p>
            </div>
            <footer class="usa-card__footer">
              <a class="usa-button usa-button--unstyled" href="#" aria-label="Vai ai dettagli di Progetto Gamma">Dettagli →</a>
            </footer>
          </div>
        </article>
      </div>
    </div>
  </div>
</section>


</div>