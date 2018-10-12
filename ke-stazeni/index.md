---
layout: default
title: Ke stažení
description: Soubory ke stažení z úřednášek, výstupy pirátů
keywords: jablonec nad nisou, ke stažení, download
soubory:
  - name: "Koaliční smlouva - 11.10.2018"
    link: "/assets/pdf/koalicni_smlouva_final_final.pdf"
  - name: "Sociální bydlení - Úvod do problematiky"
    link: "/assets/pptx/Jablonec soc bydleni.pptx"
  - name: "Koncepce dostupného bydlení v Jablonci"
    link: "/assets/pptx/PREZ - Koncepce dostupneho bydleni v Jablonci.pptx"
  - name: "Co může obec udělat v oblasti sociálního bydlení"
    link: "/assets/pptx/SB obce - PSB.pptx"
---
<div class="row">
  <div class="medium-12 columns">

    <div class="o-section">
      <div class="o-section-inner">
          <header class="c-page-header">
            <h1 itemprop="headline" class="c-page-title">Ke stažení</h1>
          </header>
      </div>
      <div class="c-content-block c-emphasized-text">
        <p>
        Soubory můžete přímo rozkliknout, případně uložit pro pozdější použití.
        </p>
        <ul>
          {% for soubor in page.soubory %}
            <li><a href="{{soubor.link}}">{{soubor.name}}</a></li>
          {% endfor %}
        </ul>
        <p>      
        </p>
      </div>  
    </div>  
  </div>
</div>
