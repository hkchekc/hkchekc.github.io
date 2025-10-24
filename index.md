---
layout: home
title: Chek Yin Choi
subtitle: 蔡卓賢
---

<style>
  .hero {
    max-width: 1000px;
    margin: 2rem auto;
    padding: 0 1rem;
    display: grid;
    grid-template-columns: 1fr 1.2fr;
    gap: 1.5rem;
    align-items: center;
  }
  .hero img {
    width: 100%;
    height: auto;
    border-radius: 12px;
    display: block;
  }
  .hero h1 {
    margin: 0 0 .25rem 0;
    font-size: clamp(1.6rem, 2.5vw, 2rem);
    line-height: 1.2;
  }
  .hero .subtitle {
    margin: 0 0 1rem 0;
    font-size: clamp(1rem, 2vw, 1.1rem);
    opacity: .8;
  }
  .lead {
    font-size: 1.05rem;
    line-height: 1.6;
    margin: 0 0 1rem 0;
  }
  .meta {
    font-size: .98rem;
    line-height: 1.5;
  }
  .refs {
    margin: .4rem 0 0 0;
    padding-left: 1.1rem;
  }
  @media (max-width: 760px) {
    .hero { grid-template-columns: 1fr; }
  }
</style>

<div class="hero">
  <figure>
    <img src="/assets/img/portrait_lowres.jpg" alt="Portrait of Chek Yin Choi">
  </figure>

  <section>
    <h1>{{ page.title }}</h1>
    <div class="subtitle">{{ page.subtitle }}</div>

    <p class="lead">
      Welcome to my site.<br>
      I am an Economics PhD student at IIES, Stockholm University.<br>
      My research interests include macroeconomics, trade, and IO.<br>
      I will be on the 25/26 job market.
    </p>

    <div class="meta">
      <strong>Main advisor:</strong> <a href="https://www.su.se/english/profiles/tbopp-1.191787">Timo Boppart</a><br>
      <strong>References:</strong>
      <ul class="refs">
        <li><a href="https://www.su.se/english/profiles/kmitm-1.196208">Kurt Mitman</a></li>
        <li><a href="https://faculty.unibocconi.eu/michelefioretti/">Michele Fioretti</a></li>
        <li><a href="https://www.su.se/english/profiles/pkrus-1.182559">Per Krusell</a></li>
      </ul>
    </div>
  </section>
</div>
