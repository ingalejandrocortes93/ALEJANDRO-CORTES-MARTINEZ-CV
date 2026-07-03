<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Alejandro Cortés | BIM Digital Construction</title>

<style>

:root{
  --bg:#070D18;
  --panel:#0B1628;
  --card:#0F1C33;
  --text:#EAF0FF;
  --muted:#9AA7BD;
  --accent:#4DA3FF;
  --border:rgba(255,255,255,0.08);
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family:system-ui, -apple-system, Segoe UI, Roboto, Arial;
  background:var(--bg);
  color:var(--text);
  overflow-x:hidden;
}

/* =========================
   HEADER
========================= */

header{
  position:fixed;
  top:0;
  width:100%;
  z-index:1000;
  background:rgba(7,13,24,0.75);
  backdrop-filter:blur(14px);
  border-bottom:1px solid var(--border);
}

nav{
  max-width:1200px;
  margin:auto;
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:16px 20px;
}

.logo{
  font-weight:700;
  letter-spacing:2px;
  font-size:13px;
}

.lang button{
  background:transparent;
  border:1px solid var(--border);
  color:var(--muted);
  padding:6px 10px;
  cursor:pointer;
  border-radius:8px;
  margin-left:6px;
}

/* =========================
   HERO (NIVEL EMPRESA)
========================= */

.hero{
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  position:relative;

  background:
    linear-gradient(rgba(0,0,0,0.55),rgba(0,0,0,0.9)),
    url("https://images.unsplash.com/photo-1503387762-592deb58ef4e");
  background-size:cover;
  background-position:center;
}

.hero-content{
  max-width:900px;
  padding:0 20px;
}

.hero-tag{
  color:var(--muted);
  letter-spacing:3px;
  font-size:12px;
}

.hero h1{
  font-size:64px;
  margin-top:10px;
  letter-spacing:2px;
}

.hero h2{
  font-size:20px;
  font-weight:400;
  color:var(--muted);
  margin-top:10px;
}

.hero p{
  margin-top:20px;
  color:var(--muted);
  max-width:700px;
  margin-inline:auto;
  line-height:1.6;
}

.hero-buttons{
  margin-top:25px;
}

.btn{
  display:inline-block;
  padding:12px 18px;
  border-radius:10px;
  text-decoration:none;
  font-size:13px;
  margin:6px;
}

.primary{
  background:var(--accent);
  color:white;
}

.secondary{
  border:1px solid var(--border);
  color:var(--text);
}

/* =========================
   SECTIONS BASE
========================= */

section{
  padding:100px 20px;
  max-width:1200px;
  margin:auto;
}

.section-title{
  font-size:28px;
  margin-bottom:10px;
}

.section-sub{
  color:var(--muted);
  margin-bottom:40px;
}

/* SERVICES */

.services-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:16px;
}

.service-card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:12px;
  padding:18px;
  transition:0.3s ease;
}

.service-card h3{
  margin-bottom:10px;
  font-size:16px;
}

.service-card p{
  color:var(--muted);
  font-size:13px;
  line-height:1.5;
}

.service-card:hover{
  transform:translateY(-6px);
  border-color:rgba(77,163,255,0.5);
}

</style>
</head>

<body>

<!-- HEADER -->
<header>
<nav>
<div class="logo">ALEJANDRO CORTÉS | BIM</div>

<div class="lang">
<button onclick="setLang('es')">ES</button>
<button onclick="setLang('en')">EN</button>
</div>
</nav>
</header>

<!-- HERO -->
<section class="hero">

<div class="hero-content">

<div class="hero-tag">DIGITAL CONSTRUCTION • BIM • ISO 19650</div>

<h1>BIM DIGITAL ENGINEERING</h1>

<h2 id="heroTitle">
Transforming design, data and construction into one system.
</h2>

<p id="heroText">
Especialista en BIM enfocado en coordinación, modelado, automatización y gestión de información bajo estándares internacionales como ISO 19650.
</p>

<div class="hero-buttons">
<a href="#about" class="btn primary">Conocer más</a>
<a href="#projects" class="btn secondary">Ver proyectos</a>
</div>

</div>

</section>

<!-- ABOUT -->
<section id="about">

<h2 class="section-title">Sobre mí</h2>
<p class="section-sub">
Especialista en BIM enfocado en coordinación, modelado, automatización y estándares ISO 19650.
</p>

</section>

<!-- SERVICES (PARTE 3 VA AQUÍ) -->
<section id="services">

<h2 class="section-title">Servicios BIM</h2>
<p class="section-sub">
Soluciones digitales para diseño, coordinación y gestión de información en construcción.
</p>

<div class="services-grid">

<div class="service-card">
<h3>BIM Modeling</h3>
<p>Modelado arquitectónico, estructural y MEP con estándares internacionales.</p>
</div>

<div class="service-card">
<h3>BIM Coordination</h3>
<p>Detección de interferencias y control de calidad del modelo.</p>
</div>

<div class="service-card">
<h3>Scan to BIM</h3>
<p>Conversión de nubes de puntos en modelos BIM.</p>
</div>

<div class="service-card">
<h3>ISO 19650</h3>
<p>Gestión de información y Common Data Environment (CDE).</p>
</div>

<div class="service-card">
<h3>Automation</h3>
<p>Optimización con Dynamo y Python.</p>
</div>

<div class="service-card">
<h3>GIS + BIM</h3>
<p>Integración geoespacial para proyectos urbanos.</p>
</div>

</div>

</section>

</section>

<!-- PROJECTS -->

<!-- ========================================================= -->
<!-- EXPERIENCE -->
<!-- ========================================================= -->

<section id="experience">

<h2 class="section-title">Experiencia</h2>
<p class="section-sub">
Trayectoria enfocada en BIM, coordinación y transformación digital en construcción.
</p>

<div class="timeline">

<div class="timeline-item">
<div class="year">2026 Regional High Specialty Nuclear Medicine Hospital</div>
<div class="content">
<h3>BIM Consultant / Digital Construction</h3>
<p>
Developed and maintained the structural BIM model.
Coordinated structural information with architectural and MEP disciplines.
Reviewed model quality and information consistency throughout project development.
</p>
</div>
</div>

<div class="timeline-item">
<div class="year">2025</div>
<div class="content">
<h3>BIM Modeler & Coordinator</h3>
<p>
Modelado arquitectónico, coordinación de interferencias (clash detection) y apoyo en proyectos de infraestructura digital.
</p>
</div>
</div>

<div class="timeline-item">
<div class="year">2024</div>
<div class="content">
<h3>Scan to BIM / Modelado Digital</h3>
<p>
Procesamiento de nubes de puntos y generación de modelos BIM para edificaciones existentes.
</p>
</div>
</div>

</div>

</section>
<section id="projects">

<h2 class="section-title">Proyectos</h2>
<p class="section-sub">Selección de trabajos BIM</p>

<div id="projectsContainer"></div>

</section>

<script>

let lang = "es";

const texts = {
  es: {
    heroTitle: "Transformando diseño, datos y construcción en un solo sistema.",
    heroText: "Especialista en BIM enfocado en coordinación, modelado, automatización y gestión de información bajo estándares internacionales como ISO 19650."
  },
  en: {
    heroTitle: "Transforming design, data and construction into one system.",
    heroText: "BIM specialist focused on coordination, modeling, automation and information management under ISO 19650 standards."
  }
};

function setLang(l){
  lang = l;
  document.getElementById("heroTitle").innerText = texts[l].heroTitle;
  document.getElementById("heroText").innerText = texts[l].heroText;
}

/* placeholder proyectos */
const projects = [
  { es:"Nido de Texcoco", en:"Nest of Texcoco" },
  { es:"Scan to BIM", en:"Scan to BIM" },
  { es:"Coordinación BIM", en:"BIM Coordination" }
];

function renderProjects(){
  const c = document.getElementById("projectsContainer");
  c.innerHTML = "";

  projects.forEach(p=>{
    const div = document.createElement("div");
    div.style.padding = "14px";
    div.style.marginBottom = "10px";
    div.style.background = "#0F1C33";
    div.style.border = "1px solid rgba(255,255,255,0.08)";
    div.style.borderRadius = "10px";

    div.innerText = lang === "es" ? p.es : p.en;

    c.appendChild(div);
  });
}

renderProjects();

/* =========================================================
   PARTE 4 — UX PRO (ANIMACIONES + EXPERIENCIA PREMIUM)
========================================================= */

/* =========================
   SMOOTH SCROLL
========================= */

document.querySelectorAll('a[href^="#"]').forEach(link => {
  link.addEventListener("click", function(e){
    e.preventDefault();

    const target = document.querySelector(this.getAttribute("href"));

    if(target){
      target.scrollIntoView({
        behavior:"smooth",
        block:"start"
      });
    }
  });
});

/* =========================
   HEADER AUTO HIDE ON SCROLL
========================= */

const header = document.querySelector("header");
let lastScroll = 0;

window.addEventListener("scroll", () => {
  const current = window.pageYOffset;

  if(current > lastScroll && current > 80){
    header.style.transform = "translateY(-100%)";
  } else {
    header.style.transform = "translateY(0)";
  }

  lastScroll = current;
});

/* =========================
   REVEAL ON SCROLL (PRO)
========================= */

const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if(entry.isIntersecting){
      entry.target.style.opacity = "1";
      entry.target.style.transform = "translateY(0)";
    }
  });
}, { threshold: 0.1 });

document.querySelectorAll(".service-card, section, .timeline-item").forEach(el => {
  el.style.opacity = "0";
  el.style.transform = "translateY(40px)";
  el.style.transition = "0.8s ease";

  observer.observe(el);
});

/* =========================
   HOVER 3D EN CARDS
========================= */

document.querySelectorAll(".service-card").forEach(card => {
  card.addEventListener("mousemove", (e) => {
    const rect = card.getBoundingClientRect();

    const x = e.clientX - rect.left;
    const y = e.clientY - rect.top;

    const centerX = rect.width / 2;
    const centerY = rect.height / 2;

    const rotateX = (y - centerY) / 18;
    const rotateY = (centerX - x) / 18;

    card.style.transform = `perspective(600px) rotateX(${rotateX}deg) rotateY(${rotateY}deg)`;
  });

  card.addEventListener("mouseleave", () => {
    card.style.transform = "perspective(600px) rotateX(0) rotateY(0)";
  });
});

/* =========================
   ENTRADA SUAVE INICIAL
========================= */

window.addEventListener("load", () => {
  document.body.style.opacity = "1";
});

/* =========================================================
   PARTE 5 — POLISH FINAL (NIVEL ESTUDIO BIM)
========================================================= */

/* =========================
   PROYECTOS CON TARJETAS PRO
========================= */

function enhanceProjectsUI() {
  const container = document.getElementById("projectsContainer");

  container.innerHTML = "";

  const projects = [
    {
      title_es: "Nido de Texcoco",
      title_en: "Nest of Texcoco",
      desc_es: "Vivienda orgánica integrada al terreno con enfoque BIM.",
      desc_en: "Organic dwelling integrated into terrain using BIM."
    },
    {
      title_es: "Scan to BIM",
      title_en: "Scan to BIM",
      desc_es: "Conversión de nube de puntos a modelo BIM.",
      desc_en: "Point cloud to BIM modeling workflow."
    },
    {
      title_es: "Coordinación BIM",
      title_en: "BIM Coordination",
      desc_es: "Detección de interferencias multidisciplinarias.",
      desc_en: "Multidisciplinary clash detection and coordination."
    }
  ];

  projects.forEach((p, i) => {

    const card = document.createElement("div");

    card.style.background = "var(--card)";
    card.style.border = "1px solid rgba(255,255,255,0.08)";
    card.style.borderRadius = "14px";
    card.style.padding = "18px";
    card.style.marginBottom = "12px";
    card.style.cursor = "pointer";
    card.style.transition = "0.3s ease";

    card.innerHTML = `
      <h3 style="margin-bottom:6px;">
        ${lang === "es" ? p.title_es : p.title_en}
      </h3>
      <p style="color:var(--muted); font-size:13px;">
        ${lang === "es" ? p.desc_es : p.desc_en}
      </p>
    `;

    card.onmouseenter = () => {
      card.style.transform = "translateY(-6px)";
      card.style.borderColor = "rgba(77,163,255,0.6)";
    };

    card.onmouseleave = () => {
      card.style.transform = "translateY(0)";
      card.style.borderColor = "rgba(255,255,255,0.08)";
    };

    container.appendChild(card);
  });
}

/* =========================
   AUTO REFRESH PROYECTOS EN CAMBIO IDIOMA
========================= */

const oldSetLang = setLang;

setLang = function(l){
  oldSetLang(l);
  enhanceProjectsUI();
};

/* =========================
   INIT FINAL
========================= */

enhanceProjectsUI();

/* =========================
   MICRO DETALLE FINAL PRO
========================= */

console.log("%cBIM PORTFOLIO LOADED ✔", "color:#4DA3FF;font-weight:bold;");

/* =========================================================
   PARTE 6 — LEVEL UP FINAL (STUDIO BIM EXPERIENCE)
========================================================= */

/* =========================
   HERO PARALLAX SUAVE
========================= */

window.addEventListener("scroll", () => {
  const hero = document.querySelector(".hero");
  if(!hero) return;

  let offset = window.pageYOffset;
  hero.style.backgroundPositionY = offset * 0.4 + "px";
});

/* =========================
   ANIMACIÓN MÁS SUAVE PARA SECCIONES
========================= */

const sections = document.querySelectorAll("section");

const sectionObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if(entry.isIntersecting){
      entry.target.style.opacity = "1";
      entry.target.style.transform = "translateY(0)";
    }
  });
}, { threshold: 0.12 });

sections.forEach(sec => {
  sec.style.opacity = "0";
  sec.style.transform = "translateY(50px)";
  sec.style.transition = "0.9s ease";

  sectionObserver.observe(sec);
});

/* =========================
   EXPERIENCE TIMELINE STYLE (SI EXISTE)
========================= */

document.querySelectorAll(".timeline-item").forEach(item => {
  item.style.position = "relative";
  item.style.paddingLeft = "18px";
  item.style.borderLeft = "2px solid rgba(77,163,255,0.3)";

  item.onmouseenter = () => {
    item.style.borderLeft = "2px solid rgba(77,163,255,0.9)";
  };

  item.onmouseleave = () => {
    item.style.borderLeft = "2px solid rgba(77,163,255,0.3)";
  };
});

/* =========================
   BOTONES MÁS PREMIUM (HOVER GLOBAL)
========================= */

document.querySelectorAll(".btn").forEach(btn => {
  btn.addEventListener("mouseenter", () => {
    btn.style.transform = "translateY(-2px)";
    btn.style.boxShadow = "0 10px 30px rgba(77,163,255,0.2)";
  });

  btn.addEventListener("mouseleave", () => {
    btn.style.transform = "translateY(0)";
    btn.style.boxShadow = "none";
  });
});

/* =========================
   DETALLE FINAL (TIPOGRAFÍA DINÁMICA SUAVE)
========================= */

document.body.style.letterSpacing = "0.2px";

/* =========================
   FINAL LOG
========================= */

console.log("%cSTUDIO BIM EXPERIENCE ACTIVE ✨", "color:#4DA3FF;font-weight:bold;");

/* =========================================================
   PARTE 7 — STUDIO BIM REAL EXPERIENCE (EDITORIAL LEVEL)
========================================================= */

/* =========================
   PROYECTOS — ESTILO PORTAFOLIO EDITORIAL
========================= */

function renderStudioProjects() {
  const container = document.getElementById("projectsContainer");
  if(!container) return;

  const projects = [
    {
      title: "Nido de Texcoco",
      subtitle: "Arquitectura orgánica + BIM integrado al terreno",
      tag: "Architecture / BIM / Parametric",
    },
    {
      title: "Scan to BIM Workflow",
      subtitle: "Procesamiento de nube de puntos a modelo BIM LOD 300+",
      tag: "Reality Capture / BIM",
    },
    {
      title: "Coordinación Multidisciplinaria",
      subtitle: "Clash detection y control de interferencias en Navisworks",
      tag: "Coordination / Construction",
    }
  ];

  container.innerHTML = "";

  projects.forEach(p => {

    const card = document.createElement("div");

    card.style.padding = "24px";
    card.style.marginBottom = "16px";
    card.style.borderBottom = "1px solid rgba(255,255,255,0.08)";
    card.style.cursor = "pointer";
    card.style.transition = "0.4s ease";

    card.innerHTML = `
      <div style="font-size:12px;color:var(--muted);letter-spacing:1px;">
        ${p.tag}
      </div>

      <div style="font-size:22px;margin-top:8px;">
        ${p.title}
      </div>

      <div style="color:var(--muted);margin-top:6px;line-height:1.5;max-width:700px;">
        ${p.subtitle}
      </div>
    `;

    card.onmouseenter = () => {
      card.style.transform = "translateX(10px)";
      card.style.borderBottom = "1px solid rgba(77,163,255,0.7)";
    };

    card.onmouseleave = () => {
      card.style.transform = "translateX(0)";
      card.style.borderBottom = "1px solid rgba(255,255,255,0.08)";
    };

    container.appendChild(card);
  });
}

/* =========================
   NAV INTERNO SUAVE (EXPERIENCIA DE AGENCIA)
========================= */

document.querySelectorAll("a[href^='#']").forEach(a => {
  a.addEventListener("click", e => {
    e.preventDefault();

    const target = document.querySelector(a.getAttribute("href"));

    if(target){
      window.scrollTo({
        top: target.offsetTop - 60,
        behavior: "smooth"
      });
    }
  });
});

/* =========================
   TIPOGRAFÍA MÁS EDITORIAL
========================= */

document.body.style.lineHeight = "1.6";

/* =========================
   EFECTO “ESTUDIO” EN SCROLL FINAL
========================= */

window.addEventListener("scroll", () => {
  const scroll = window.scrollY;

  document.querySelectorAll(".service-card").forEach((el, i) => {
    el.style.transform = `translateY(${Math.sin(scroll * 0.002 + i) * 2}px)`;
  });
});

/* =========================
   INIT FINAL SISTEMA STUDIO
========================= */

renderStudioProjects();

console.log("%cSTUDIO BIM EDITORIAL MODE ACTIVE 🏢", "color:#4DA3FF;font-weight:bold;");

/* =========================================================
   PARTE 8 — STUDIO BIM SIGNATURE (FIRM LEVEL EXPERIENCE)
========================================================= */

/* =========================
   HERO MÁS CINEMÁTICO (DEPTH FEEL)
========================= */

const hero = document.querySelector(".hero");

if(hero){
  window.addEventListener("mousemove", (e) => {

    const x = (window.innerWidth / 2 - e.clientX) / 40;
    const y = (window.innerHeight / 2 - e.clientY) / 40;

    hero.style.transform = `rotateX(${y}deg) rotateY(${x}deg) scale(1.01)`;
    hero.style.transition = "0.2s ease";
  });

  window.addEventListener("mouseleave", () => {
    hero.style.transform = "rotateX(0) rotateY(0) scale(1)";
  });
}

/* =========================
   PROYECTOS — STORY MODE (CASOS DE ESTUDIO)
========================= */

function studioCaseStudies() {
  const container = document.getElementById("projectsContainer");
  if(!container) return;

  const cases = [
    {
      title: "Nido de Texcoco",
      role: "BIM Integration / Concept + Development",
      description:
        "Proyecto de vivienda orgánica donde se integra topografía real, modelado BIM y diseño paramétrico para optimizar implantación en terreno.",
    },
    {
      title: "Scan to BIM Workflow",
      role: "Reality Capture / BIM Modeling",
      description:
        "Flujo completo de nube de puntos a modelo BIM coordinado, optimizando documentación de edificaciones existentes.",
    },
    {
      title: "BIM Coordination System",
      role: "Clash Detection / Coordination Management",
      description:
        "Sistema de coordinación multidisciplinaria con detección de interferencias y control de calidad del modelo.",
    }
  ];

  container.innerHTML = "";

  cases.forEach(c => {

    const card = document.createElement("div");

    card.style.padding = "28px";
    card.style.marginBottom = "20px";
    card.style.borderLeft = "2px solid rgba(77,163,255,0.3)";
    card.style.transition = "0.4s ease";
    card.style.cursor = "pointer";

    card.innerHTML = `
      <div style="font-size:12px;color:var(--muted);letter-spacing:1px;">
        ${c.role}
      </div>

      <div style="font-size:26px;margin-top:10px;">
        ${c.title}
      </div>

      <div style="margin-top:12px;color:var(--muted);max-width:800px;line-height:1.6;">
        ${c.description}
      </div>
    `;

    card.onmouseenter = () => {
      card.style.borderLeft = "2px solid rgba(77,163,255,0.9)";
      card.style.transform = "translateX(12px)";
    };

    card.onmouseleave = () => {
      card.style.borderLeft = "2px solid rgba(77,163,255,0.3)";
      card.style.transform = "translateX(0)";
    };

    container.appendChild(card);
  });
}

/* =========================
   MICRO INTERACCIÓN GLOBAL SUAVE
========================= */

document.querySelectorAll("section").forEach(sec => {
  sec.addEventListener("mouseenter", () => {
    sec.style.transition = "0.4s ease";
    sec.style.filter = "brightness(1.02)";
  });

  sec.addEventListener("mouseleave", () => {
    sec.style.filter = "brightness(1)";
  });
});

/* =========================
   EFECTO PARALLAX GLOBAL SUAVE
========================= */

window.addEventListener("scroll", () => {
  const scroll = window.scrollY;

  document.querySelectorAll("section").forEach((sec, i) => {
    sec.style.transform = `translateY(${scroll * 0.01 * (i % 2 === 0 ? 1 : -1)}px)`;
  });
});

/* =========================
   INIT FINAL STUDIO MODE
========================= */

studioCaseStudies();

console.log("%cSTUDIO BIM SIGNATURE MODE ACTIVE 🏛️", "color:#4DA3FF;font-weight:bold;");

</script>

</body>
</html>
