---
layout: default
title: Software developer
---

<div class="portfolio">
  <section class="hero" aria-labelledby="intro-title">
    <p class="eyebrow">Mihaly Vizhanyo · Software developer</p>
    <h1 id="intro-title">Building software that stays understandable.</h1>
    <p class="hero-copy">I turn complex rules into approachable, maintainable applications—from RPG character generators and dice systems to reliable everyday services.</p>
    <div class="hero-actions">
      <a class="button button-primary" href="#work">View selected work</a>
      <a class="button button-secondary" href="https://github.com/vizmi">GitHub profile <span aria-hidden="true">↗</span></a>
    </div>
  </section>

  <section class="principles" aria-labelledby="principles-title">
    <div class="section-heading">
      <p class="eyebrow">How I work</p>
      <h2 id="principles-title">Engineering principles</h2>
    </div>
    <div class="principle-grid">
      <article class="principle">
        <span class="principle-number">01</span>
        <h3>Choose the right tool for the problem</h3>
        <p>Technologies are means, not identities. I choose the approach that best fits the constraints and makes the work straightforward.</p>
      </article>
      <article class="principle">
        <span class="principle-number">02</span>
        <h3>Prefer the simplest complete solution</h3>
        <p>Complexity has a long-term cost, so I avoid it unless it genuinely earns its place.</p>
      </article>
      <article class="principle">
        <span class="principle-number">03</span>
        <h3>Make code tell a story</h3>
        <p>Good code communicates not only what it does, but why it was designed that way—making it easier to understand, trust, and safely evolve.</p>
      </article>
    </div>
  </section>

  <section class="work" id="work" aria-labelledby="work-title">
    <div class="section-heading">
      <p class="eyebrow">Selected work</p>
      <h2 id="work-title">Three ways I solve problems</h2>
      <p>Each project starts with a concrete constraint and makes its technical choices visible.</p>
    </div>

    <div class="project-grid">
      <article class="project project-featured">
        <div class="project-art cloning-art" aria-hidden="true">
          <div class="art-window">
            <span></span><span></span><span></span>
            <div class="art-sheet"><i></i><b></b><b></b><b></b><em></em></div>
          </div>
          <p>CLONING<br>VAT</p>
        </div>
        <div class="project-content">
          <p class="project-label">Vue application</p>
          <h3>Cloning Vat</h3>
          <p class="project-summary">A Cyberpunk 2020 character generator that turns a dense ruleset into a guided, exportable character-building experience.</p>
          <ul class="project-points">
            <li>Models interdependent character choices and derived statistics.</li>
            <li>Separates domain logic into composables with automated tests.</li>
            <li>Supports importing, exporting, and sharing character data.</li>
          </ul>
          <p class="tags"><span>Vue 3</span><span>TypeScript</span><span>Vuetify</span><span>Vitest</span></p>
          <p class="project-links"><a href="https://vizmi.github.io/cloning-vat">Live demo <span aria-hidden="true">↗</span></a><a href="https://github.com/vizmi/cloning-vat">Source <span aria-hidden="true">↗</span></a></p>
        </div>
      </article>

      <article class="project">
        <div class="project-art rolldozer-art" aria-hidden="true">
          <div class="die">20</div>
          <div class="roll-line"><span>2d6 + 3</span><b>15</b></div>
          <div class="roll-line muted"><span>1d20</span><b>18</b></div>
        </div>
        <div class="project-content">
          <p class="project-label">React application</p>
          <h3>Rolldozer</h3>
          <p class="project-summary">A focused dice roller that makes repeat rolls fast, with history and saved favourites.</p>
          <ul class="project-points">
            <li>Parses standard RPG dice expressions.</li>
            <li>Persists useful roll presets locally.</li>
            <li>Offers English and Hungarian interfaces.</li>
          </ul>
          <p class="tags"><span>React</span><span>Tailwind CSS</span><span>i18next</span><span>Vitest</span></p>
          <p class="project-links"><a href="https://vizmi.github.io/rolldozer">Live demo <span aria-hidden="true">↗</span></a><a href="https://github.com/vizmi/rolldozer">Source <span aria-hidden="true">↗</span></a></p>
        </div>
      </article>

      <article class="project">
        <div class="project-art parking-art" aria-hidden="true">
          <div class="gate">GATE <b>OPEN</b></div>
          <div class="parking-spots"><i>01</i><i>02</i><i>03</i><i>04</i></div>
          <p>Atomic reservation</p>
        </div>
        <div class="project-content">
          <p class="project-label">Backend service</p>
          <h3>Parking Manager</h3>
          <p class="project-summary">A parking-space assignment service designed so simultaneous arrivals can never receive the same spot.</p>
          <ul class="project-points">
            <li>Uses Redis atomic operations to prevent double-booking.</li>
            <li>Assigns the lowest available space in a single round trip.</li>
            <li>Tests the concurrency guarantee with real infrastructure.</li>
          </ul>
          <p class="tags"><span>Java</span><span>Spring Boot</span><span>Redis</span><span>Docker</span></p>
          <p class="project-links"><a href="https://github.com/vizmi/parking-mgr">Source &amp; design notes <span aria-hidden="true">↗</span></a></p>
        </div>
      </article>
    </div>
  </section>

  <section class="contact" aria-labelledby="contact-title">
    <p class="eyebrow">Get in touch</p>
    <h2 id="contact-title">Interested in how I think and build?</h2>
    <p>Explore the code behind these projects, or get in touch through GitHub.</p>
    <a class="button button-primary" href="https://github.com/vizmi">Visit GitHub <span aria-hidden="true">↗</span></a>
  </section>
</div>
