<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ARQHAUS — Arquitetura & Design</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Bebas+Neue&family=Jost:wght@200;300;400;500&display=swap" rel="stylesheet">
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --concrete: #c8c4bc;
      --stone: #8a8580;
      --charcoal: #2a2825;
      --graphite: #1a1917;
      --warm-white: #f4f2ee;
      --cream: #ede9e3;
      --copper: #8b6542;
      --gold: #b8935a;
      --text-main: #1a1917;
      --text-muted: #6b6760;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'Jost', sans-serif;
      background: var(--graphite);
      color: var(--warm-white);
      overflow-x: hidden;
      cursor: none;
    }

    /* Custom cursor */
    .cursor {
      position: fixed;
      width: 8px; height: 8px;
      background: var(--gold);
      border-radius: 50%;
      pointer-events: none;
      z-index: 9999;
      transition: transform 0.1s;
      transform: translate(-50%, -50%);
    }
    .cursor-ring {
      position: fixed;
      width: 32px; height: 32px;
      border: 1px solid rgba(184,147,90,0.5);
      border-radius: 50%;
      pointer-events: none;
      z-index: 9998;
      transition: transform 0.25s ease, width 0.3s, height 0.3s;
      transform: translate(-50%, -50%);
    }
    body:hover .cursor-ring { opacity: 1; }

    /* NAV */
    nav {
      position: fixed; top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 28px 60px;
      mix-blend-mode: normal;
      transition: background 0.4s, padding 0.4s;
    }
    nav.scrolled {
      background: rgba(26,25,23,0.95);
      backdrop-filter: blur(12px);
      padding: 18px 60px;
      border-bottom: 1px solid rgba(255,255,255,0.05);
    }
    .nav-logo {
      display: flex;
      align-items: center;
      gap: 12px;
      text-decoration: none;
    }
    .logo-mark {
      width: 42px; height: 42px;
      position: relative;
    }
    .logo-mark svg { width: 100%; height: 100%; }
    .logo-wordmark {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 22px;
      letter-spacing: 0.2em;
      color: var(--warm-white);
    }
    .nav-links {
      display: flex;
      gap: 40px;
      list-style: none;
    }
    .nav-links a {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 12px;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(244,242,238,0.7);
      text-decoration: none;
      transition: color 0.3s;
      position: relative;
    }
    .nav-links a::after {
      content: '';
      position: absolute;
      bottom: -4px; left: 0;
      width: 0; height: 1px;
      background: var(--gold);
      transition: width 0.3s;
    }
    .nav-links a:hover { color: var(--warm-white); }
    .nav-links a:hover::after { width: 100%; }
    .nav-cta {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 11px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--graphite);
      background: var(--gold);
      padding: 10px 24px;
      text-decoration: none;
      transition: background 0.3s, transform 0.2s;
    }
    .nav-cta:hover { background: var(--copper); transform: translateY(-1px); }

    /* HERO */
    .hero {
      position: relative;
      height: 100vh;
      min-height: 700px;
      display: flex;
      align-items: flex-end;
      overflow: hidden;
    }
    .hero-bg {
      position: absolute; inset: 0;
      background:
        linear-gradient(160deg, rgba(26,25,23,0.3) 0%, rgba(26,25,23,0.85) 100%),
        url('https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?w=1600&q=80') center/cover no-repeat;
    }
    .hero-noise {
      position: absolute; inset: 0;
      opacity: 0.04;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)'/%3E%3C/svg%3E");
    }
    .hero-grid-lines {
      position: absolute; inset: 0;
      background-image:
        linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
      background-size: 80px 80px;
    }
    .hero-content {
      position: relative;
      padding: 0 60px 80px;
      max-width: 900px;
      animation: heroFadeUp 1.2s cubic-bezier(0.16, 1, 0.3, 1) both;
    }
    @keyframes heroFadeUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .hero-eyebrow {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 11px;
      letter-spacing: 0.35em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 24px;
      display: flex;
      align-items: center;
      gap: 16px;
    }
    .hero-eyebrow::before {
      content: '';
      display: block;
      width: 40px; height: 1px;
      background: var(--gold);
    }
    .hero-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: clamp(72px, 10vw, 140px);
      line-height: 0.92;
      letter-spacing: 0.02em;
      margin-bottom: 32px;
      color: var(--warm-white);
    }
    .hero-title em {
      font-family: 'Cormorant Garamond', serif;
      font-style: italic;
      font-weight: 300;
      color: var(--concrete);
    }
    .hero-sub {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 15px;
      line-height: 1.8;
      color: rgba(244,242,238,0.65);
      max-width: 480px;
      margin-bottom: 48px;
    }
    .hero-actions {
      display: flex;
      gap: 20px;
      align-items: center;
    }
    .btn-primary {
      font-family: 'Jost', sans-serif;
      font-weight: 400;
      font-size: 12px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--graphite);
      background: var(--gold);
      padding: 16px 36px;
      text-decoration: none;
      transition: background 0.3s, transform 0.2s;
      display: inline-block;
    }
    .btn-primary:hover { background: var(--copper); transform: translateY(-2px); }
    .btn-ghost {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 12px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--warm-white);
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 10px;
      transition: color 0.3s;
    }
    .btn-ghost:hover { color: var(--gold); }
    .hero-scroll {
      position: absolute;
      right: 60px; bottom: 80px;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 12px;
      color: rgba(244,242,238,0.4);
      font-size: 10px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
    }
    .hero-scroll-line {
      width: 1px;
      height: 60px;
      background: linear-gradient(to bottom, transparent, rgba(184,147,90,0.6));
      animation: scrollLine 2s ease-in-out infinite;
    }
    @keyframes scrollLine {
      0%, 100% { transform: scaleY(0); transform-origin: top; }
      50% { transform: scaleY(1); transform-origin: top; }
    }

    /* STATS BAND */
    .stats-band {
      background: var(--charcoal);
      border-top: 1px solid rgba(255,255,255,0.06);
      border-bottom: 1px solid rgba(255,255,255,0.06);
      padding: 40px 60px;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 1px;
    }
    .stat-item {
      padding: 0 40px;
      border-right: 1px solid rgba(255,255,255,0.06);
      animation: statReveal 0.8s ease both;
    }
    .stat-item:first-child { padding-left: 0; }
    .stat-item:last-child { border-right: none; }
    .stat-num {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 300;
      font-size: 52px;
      line-height: 1;
      color: var(--gold);
      margin-bottom: 6px;
    }
    .stat-label {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 11px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--stone);
    }

    /* SECTION COMMONS */
    section { padding: 120px 60px; }
    .section-tag {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 10px;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 20px;
      display: flex;
      align-items: center;
      gap: 14px;
    }
    .section-tag::before {
      content: '';
      display: block;
      width: 30px; height: 1px;
      background: var(--gold);
    }
    .section-title {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 300;
      font-size: clamp(42px, 5vw, 68px);
      line-height: 1.1;
      color: var(--warm-white);
    }
    .section-title em {
      font-style: italic;
      color: var(--concrete);
    }

    /* ABOUT */
    .about { background: var(--graphite); }
    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 100px;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }
    .about-image-wrap {
      position: relative;
    }
    .about-image {
      width: 100%;
      aspect-ratio: 3/4;
      object-fit: cover;
      filter: grayscale(30%);
    }
    .about-image-accent {
      position: absolute;
      top: -24px; right: -24px;
      width: 60%; height: 60%;
      border: 1px solid rgba(184,147,90,0.3);
      z-index: -1;
    }
    .about-image-tag {
      position: absolute;
      bottom: 30px; left: -30px;
      background: var(--gold);
      color: var(--graphite);
      padding: 20px 24px;
      font-family: 'Bebas Neue', sans-serif;
      font-size: 14px;
      letter-spacing: 0.15em;
    }
    .about-text {
      padding-right: 20px;
    }
    .about-text p {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 15px;
      line-height: 1.9;
      color: rgba(244,242,238,0.65);
      margin-top: 28px;
    }
    .about-pillars {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      margin-top: 40px;
    }
    .pillar {
      border-left: 1px solid rgba(184,147,90,0.4);
      padding: 0 0 0 20px;
    }
    .pillar-title {
      font-family: 'Jost', sans-serif;
      font-weight: 500;
      font-size: 12px;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 6px;
    }
    .pillar-text {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 13px;
      color: rgba(244,242,238,0.5);
    }

    /* SERVICES */
    .services {
      background: var(--charcoal);
      position: relative;
      overflow: hidden;
    }
    .services::before {
      content: 'SERVIÇOS';
      position: absolute;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      font-family: 'Bebas Neue', sans-serif;
      font-size: 280px;
      color: rgba(255,255,255,0.015);
      white-space: nowrap;
      pointer-events: none;
    }
    .services-header {
      max-width: 1200px;
      margin: 0 auto 70px;
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
    }
    .services-desc {
      max-width: 360px;
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 14px;
      line-height: 1.8;
      color: rgba(244,242,238,0.55);
    }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1px;
      max-width: 1200px;
      margin: 0 auto;
      background: rgba(255,255,255,0.05);
    }
    .service-card {
      background: var(--charcoal);
      padding: 48px 40px;
      transition: background 0.4s;
      position: relative;
      overflow: hidden;
    }
    .service-card::after {
      content: '';
      position: absolute;
      bottom: 0; left: 0;
      width: 0; height: 2px;
      background: var(--gold);
      transition: width 0.5s cubic-bezier(0.16,1,0.3,1);
    }
    .service-card:hover { background: rgba(42,40,37,0.8); }
    .service-card:hover::after { width: 100%; }
    .service-num {
      font-family: 'Cormorant Garamond', serif;
      font-size: 48px;
      font-weight: 300;
      color: rgba(184,147,90,0.2);
      line-height: 1;
      margin-bottom: 24px;
    }
    .service-icon {
      font-size: 28px;
      margin-bottom: 20px;
    }
    .service-title {
      font-family: 'Jost', sans-serif;
      font-weight: 500;
      font-size: 16px;
      letter-spacing: 0.05em;
      color: var(--warm-white);
      margin-bottom: 16px;
    }
    .service-text {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 13px;
      line-height: 1.8;
      color: rgba(244,242,238,0.5);
    }

    /* PORTFOLIO */
    .portfolio { background: var(--graphite); }
    .portfolio-header {
      max-width: 1200px;
      margin: 0 auto 60px;
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
    }
    .portfolio-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      grid-template-rows: auto auto;
      gap: 16px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .portfolio-item {
      position: relative;
      overflow: hidden;
      cursor: pointer;
    }
    .portfolio-item:first-child {
      grid-row: span 2;
    }
    .portfolio-img {
      width: 100%;
      height: 100%;
      min-height: 280px;
      object-fit: cover;
      filter: grayscale(20%) brightness(0.85);
      transition: transform 0.7s cubic-bezier(0.16,1,0.3,1), filter 0.5s;
      display: block;
    }
    .portfolio-item:first-child .portfolio-img { min-height: 600px; }
    .portfolio-item:hover .portfolio-img {
      transform: scale(1.04);
      filter: grayscale(0%) brightness(0.9);
    }
    .portfolio-overlay {
      position: absolute; inset: 0;
      background: linear-gradient(to top, rgba(26,25,23,0.9) 0%, transparent 50%);
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 32px;
      opacity: 0;
      transition: opacity 0.4s;
    }
    .portfolio-item:hover .portfolio-overlay { opacity: 1; }
    .portfolio-cat {
      font-size: 10px;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 8px;
    }
    .portfolio-name {
      font-family: 'Cormorant Garamond', serif;
      font-size: 26px;
      font-weight: 400;
      color: var(--warm-white);
    }

    /* TEAM */
    .team {
      background: var(--charcoal);
      position: relative;
    }
    .team-header {
      max-width: 1200px;
      margin: 0 auto 70px;
    }
    .team-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 24px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .team-card {
      text-align: center;
    }
    .team-photo {
      width: 100%;
      aspect-ratio: 3/4;
      object-fit: cover;
      filter: grayscale(60%) brightness(0.8);
      transition: filter 0.5s;
      margin-bottom: 20px;
    }
    .team-card:hover .team-photo {
      filter: grayscale(20%) brightness(0.95);
    }
    .team-name {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 400;
      font-size: 18px;
      color: var(--warm-white);
      margin-bottom: 6px;
    }
    .team-role {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 11px;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: var(--stone);
    }

    /* IDENTITY SECTION */
    .identity {
      background: var(--graphite);
      position: relative;
      overflow: hidden;
    }
    .identity-inner {
      max-width: 1200px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 100px;
      align-items: center;
    }
    .identity-cards {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }
    .identity-card {
      background: rgba(42,40,37,0.6);
      border: 1px solid rgba(255,255,255,0.06);
      padding: 36px 28px;
      transition: border-color 0.3s, transform 0.3s;
    }
    .identity-card:hover {
      border-color: rgba(184,147,90,0.3);
      transform: translateY(-4px);
    }
    .identity-card-icon {
      font-size: 24px;
      margin-bottom: 16px;
    }
    .identity-card-title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 20px;
      letter-spacing: 0.1em;
      color: var(--gold);
      margin-bottom: 12px;
    }
    .identity-card-text {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 13px;
      line-height: 1.8;
      color: rgba(244,242,238,0.55);
    }

    /* CONTACT */
    .contact {
      background: var(--charcoal);
      position: relative;
      overflow: hidden;
    }
    .contact::before {
      content: '';
      position: absolute;
      top: -200px; right: -200px;
      width: 600px; height: 600px;
      background: radial-gradient(circle, rgba(184,147,90,0.06) 0%, transparent 70%);
      pointer-events: none;
    }
    .contact-inner {
      max-width: 1200px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 100px;
    }
    .contact-info p {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 15px;
      line-height: 1.8;
      color: rgba(244,242,238,0.6);
      margin-top: 24px;
      margin-bottom: 40px;
    }
    .contact-detail {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .contact-item {
      display: flex;
      gap: 20px;
      align-items: flex-start;
    }
    .contact-item-icon {
      color: var(--gold);
      font-size: 18px;
      margin-top: 2px;
      flex-shrink: 0;
    }
    .contact-item-label {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 10px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--stone);
      margin-bottom: 4px;
    }
    .contact-item-value {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 14px;
      color: var(--warm-white);
    }
    .contact-form {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .form-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 16px;
    }
    .form-group {
      display: flex;
      flex-direction: column;
      gap: 8px;
    }
    .form-label {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 10px;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--stone);
    }
    .form-input, .form-textarea {
      background: rgba(26,25,23,0.6);
      border: 1px solid rgba(255,255,255,0.08);
      color: var(--warm-white);
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 14px;
      padding: 14px 16px;
      outline: none;
      transition: border-color 0.3s;
      width: 100%;
      resize: vertical;
    }
    .form-input:focus, .form-textarea:focus {
      border-color: rgba(184,147,90,0.5);
    }
    .form-textarea { min-height: 120px; }
    .form-btn {
      font-family: 'Jost', sans-serif;
      font-weight: 400;
      font-size: 12px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--graphite);
      background: var(--gold);
      border: none;
      padding: 16px 36px;
      cursor: none;
      transition: background 0.3s, transform 0.2s;
      align-self: flex-start;
    }
    .form-btn:hover { background: var(--copper); transform: translateY(-2px); }

    /* LOGO SECTION */
    .logo-section {
      background: var(--graphite);
      padding: 100px 60px;
      text-align: center;
    }
    .logo-display {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 24px;
      margin-bottom: 16px;
    }
    .logo-display-mark {
      width: 80px;
    }
    .logo-display-name {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 72px;
      letter-spacing: 0.15em;
      color: var(--warm-white);
    }
    .logo-tagline {
      font-family: 'Cormorant Garamond', serif;
      font-style: italic;
      font-size: 18px;
      color: var(--stone);
      letter-spacing: 0.1em;
    }

    /* FOOTER */
    footer {
      background: var(--graphite);
      border-top: 1px solid rgba(255,255,255,0.06);
      padding: 50px 60px 30px;
    }
    .footer-top {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 50px;
    }
    .footer-brand .logo-wordmark { font-size: 28px; }
    .footer-tagline {
      font-family: 'Cormorant Garamond', serif;
      font-style: italic;
      font-size: 14px;
      color: var(--stone);
      margin-top: 8px;
    }
    .footer-links {
      display: flex;
      gap: 60px;
    }
    .footer-col-title {
      font-family: 'Jost', sans-serif;
      font-weight: 500;
      font-size: 11px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 20px;
    }
    .footer-col ul {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .footer-col ul a {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 13px;
      color: rgba(244,242,238,0.5);
      text-decoration: none;
      transition: color 0.3s;
    }
    .footer-col ul a:hover { color: var(--warm-white); }
    .footer-bottom {
      border-top: 1px solid rgba(255,255,255,0.06);
      padding-top: 24px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .footer-copy {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 11px;
      color: rgba(244,242,238,0.3);
    }
    .footer-cnae {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      font-size: 10px;
      color: rgba(244,242,238,0.2);
      text-align: right;
    }

    /* REVEAL ANIMATION */
    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.8s ease, transform 0.8s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: none;
    }
    .reveal-delay-1 { transition-delay: 0.1s; }
    .reveal-delay-2 { transition-delay: 0.2s; }
    .reveal-delay-3 { transition-delay: 0.3s; }
    .reveal-delay-4 { transition-delay: 0.4s; }

    /* MOBILE */
    @media (max-width: 900px) {
      nav { padding: 20px 24px; }
      nav.scrolled { padding: 14px 24px; }
      .nav-links, .nav-cta { display: none; }
      section { padding: 80px 24px; }
      .hero-content { padding: 0 24px 60px; }
      .hero-scroll { display: none; }
      .stats-band { grid-template-columns: 1fr 1fr; padding: 30px 24px; gap: 30px; }
      .stat-item { border-right: none; padding: 0; }
      .about-grid, .identity-inner, .contact-inner { grid-template-columns: 1fr; gap: 50px; }
      .services-grid { grid-template-columns: 1fr; }
      .services-header { flex-direction: column; gap: 20px; }
      .portfolio-grid { grid-template-columns: 1fr; }
      .portfolio-item:first-child { grid-row: auto; }
      .team-grid { grid-template-columns: repeat(2, 1fr); }
      .identity-cards { grid-template-columns: 1fr; }
      .footer-top { flex-direction: column; gap: 40px; }
      .footer-links { gap: 30px; flex-wrap: wrap; }
      .form-row { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

  <!-- Custom Cursor -->
  <div class="cursor" id="cursor"></div>
  <div class="cursor-ring" id="cursorRing"></div>

  <!-- NAV -->
  <nav id="navbar">
    <a href="#" class="nav-logo">
      <div class="logo-mark">
        <svg viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
          <!-- A glyph -->
          <path d="M10 48 L30 12 L50 48" stroke="#f4f2ee" stroke-width="3" fill="none" stroke-linecap="square"/>
          <path d="M19 34 L41 34" stroke="#f4f2ee" stroke-width="3"/>
          <!-- H glyph internal crossbar styled as building -->
          <path d="M28 12 L28 20" stroke="#b8935a" stroke-width="2.5"/>
          <path d="M32 12 L32 20" stroke="#b8935a" stroke-width="2.5"/>
          <path d="M28 16 L32 16" stroke="#b8935a" stroke-width="2"/>
        </svg>
      </div>
      <span class="logo-wordmark">ARQHAUS</span>
    </a>
    <ul class="nav-links">
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#servicos">Serviços</a></li>
      <li><a href="#projetos">Projetos</a></li>
      <li><a href="#equipe">Equipe</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>
    <a href="#contato" class="nav-cta">Solicitar Orçamento</a>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-bg"></div>
    <div class="hero-noise"></div>
    <div class="hero-grid-lines"></div>
    <div class="hero-content">
      <div class="hero-eyebrow">Arquitetura & Design — Foz do Iguaçu</div>
      <h1 class="hero-title">
        Espaços que<br>
        <em>transformam</em><br>
        vidas
      </h1>
      <p class="hero-sub">
        Projetamos e executamos sonhos residenciais e comerciais com conforto, personalidade e integração com a natureza em cada detalhe.
      </p>
      <div class="hero-actions">
        <a href="#projetos" class="btn-primary">Ver Projetos</a>
        <a href="#sobre" class="btn-ghost">
          Conheça a ARQHAUS
          <svg width="20" height="12" viewBox="0 0 20 12" fill="none"><path d="M0 6h18M14 1l5 5-5 5" stroke="currentColor" stroke-width="1.5"/></svg>
        </a>
      </div>
    </div>
    <div class="hero-scroll">
      <span>Rolar</span>
      <div class="hero-scroll-line"></div>
    </div>
  </section>

  <!-- STATS -->
  <div class="stats-band">
    <div class="stat-item reveal">
      <div class="stat-num">5</div>
      <div class="stat-label">Arquitetos Especialistas</div>
    </div>
    <div class="stat-item reveal reveal-delay-1">
      <div class="stat-num">100+</div>
      <div class="stat-label">Projetos Realizados</div>
    </div>
    <div class="stat-item reveal reveal-delay-2">
      <div class="stat-num">15+</div>
      <div class="stat-label">Anos de Experiência</div>
    </div>
    <div class="stat-item reveal reveal-delay-3">
      <div class="stat-num">3</div>
      <div class="stat-label">CNAEs Especializados</div>
    </div>
  </div>

  <!-- ABOUT -->
  <section class="about" id="sobre">
    <div class="about-grid">
      <div class="about-image-wrap reveal">
        <img class="about-image"
          src="https://images.unsplash.com/photo-1487958449943-2429e8be8625?w=800&q=80"
          alt="Arquitetura ARQHAUS">
        <div class="about-image-accent"></div>
        <div class="about-image-tag">
          Foz do Iguaçu — PR<br>
          Fundada 2024
        </div>
      </div>
      <div class="about-text reveal reveal-delay-2">
        <div class="section-tag">Sobre Nós</div>
        <h2 class="section-title">
          Onde técnica <em>encontra</em> estética
        </h2>
        <p>
          A ARQHAUS é um escritório de arquitetura e urbanismo sediado em Foz do Iguaçu, formado por cinco arquitetas e arquiteto altamente especializados, comprometidos com a excelência técnica e a beleza funcional.
        </p>
        <p>
          Nossa missão é projetar e executar sonhos residenciais e comerciais trazendo conforto, personalidade e integração com a natureza em cada projeto — da concepção à entrega.
        </p>
        <div class="about-pillars">
          <div class="pillar">
            <div class="pillar-title">Missão</div>
            <div class="pillar-text">Projetar sonhos com conforto e personalidade</div>
          </div>
          <div class="pillar">
            <div class="pillar-title">Visão</div>
            <div class="pillar-text">Referência em arquitetura na região de Iguaçu</div>
          </div>
          <div class="pillar">
            <div class="pillar-title">Ética</div>
            <div class="pillar-text">Compromisso e responsabilidade em cada entrega</div>
          </div>
          <div class="pillar">
            <div class="pillar-title">Propósito</div>
            <div class="pillar-text">Soluções que integram segurança e bem-estar</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SERVICES -->
  <section class="services" id="servicos">
    <div class="services-header">
      <div>
        <div class="section-tag reveal">O que fazemos</div>
        <h2 class="section-title reveal reveal-delay-1">
          Serviços <em>completos</em><br>em arquitetura
        </h2>
      </div>
      <p class="services-desc reveal reveal-delay-2">
        Da concepção ao acabamento, oferecemos soluções integradas em projeto e execução, seguindo as diretrizes do CAU/BR.
      </p>
    </div>
    <div class="services-grid">
      <div class="service-card reveal">
        <div class="service-num">01</div>
        <div class="service-title">Projeto Arquitetônico</div>
        <p class="service-text">Levantamento, projeto arquitetônico, reforma, adequação de acessibilidade e documentação técnica completa.</p>
      </div>
      <div class="service-card reveal reveal-delay-1">
        <div class="service-num">02</div>
        <div class="service-title">Arquitetura de Interiores</div>
        <p class="service-text">Projeto e execução de interiores, reforma, mobiliário planejado e design de ambientes residenciais e comerciais.</p>
      </div>
      <div class="service-card reveal reveal-delay-2">
        <div class="service-num">03</div>
        <div class="service-title">Conforto Ambiental</div>
        <p class="service-text">Luminotécnica, acústica, ventilação, climatização (HVAC) e sistemas de renovação de ar de alta complexidade.</p>
      </div>
      <div class="service-card reveal">
        <div class="service-num">04</div>
        <div class="service-title">Instalações Prediais</div>
        <p class="service-text">Projetos e execução hidrossanitária, gás canalizado, gases medicinais, prevenção de incêndio e elétrica de baixa tensão.</p>
      </div>
      <div class="service-card reveal reveal-delay-1">
        <div class="service-num">05</div>
        <div class="service-title">Arquitetura Paisagística</div>
        <p class="service-text">Projeto paisagístico, recuperação ambiental, manejo e conservação de áreas externas integradas à edificação.</p>
      </div>
      <div class="service-card reveal reveal-delay-2">
        <div class="service-num">06</div>
        <div class="service-title">Gestão & Execução</div>
        <p class="service-text">Supervisão, direção e gerenciamento de obra. Assessoria técnica, vistorias, laudos e consultoria especializada.</p>
      </div>
    </div>
  </section>

  <!-- PORTFOLIO -->
  <section class="portfolio" id="projetos">
    <div class="portfolio-header">
      <div>
        <div class="section-tag reveal">Portfólio</div>
        <h2 class="section-title reveal reveal-delay-1">
          Projetos que <em>inspiram</em>
        </h2>
      </div>
      <a href="#contato" class="btn-ghost reveal reveal-delay-2">
        Ver todos
        <svg width="20" height="12" viewBox="0 0 20 12" fill="none"><path d="M0 6h18M14 1l5 5-5 5" stroke="currentColor" stroke-width="1.5"/></svg>
      </a>
    </div>
    <div class="portfolio-grid">
      <div class="portfolio-item reveal">
        <img class="portfolio-img"
          src="https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?w=800&q=80"
          alt="Residência Contemporânea">
        <div class="portfolio-overlay">
          <div class="portfolio-cat">Residencial</div>
          <div class="portfolio-name">Casa Iguaçu</div>
        </div>
      </div>
      <div class="portfolio-item reveal reveal-delay-1">
        <img class="portfolio-img"
          src="https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?w=800&q=80"
          alt="Interiores">
        <div class="portfolio-overlay">
          <div class="portfolio-cat">Interiores</div>
          <div class="portfolio-name">Studio Verde</div>
        </div>
      </div>
      <div class="portfolio-item reveal reveal-delay-2">
        <img class="portfolio-img"
          src="https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?w=800&q=80"
          alt="Comercial">
        <div class="portfolio-overlay">
          <div class="portfolio-cat">Comercial</div>
          <div class="portfolio-name">Edifício Parque</div>
        </div>
      </div>
    </div>
  </section>

  <!-- IDENTITY -->
  <section class="identity">
    <div class="identity-inner">
      <div class="reveal">
        <div class="section-tag">Nossa identidade</div>
        <h2 class="section-title">
          Valores que <em>guiam</em><br>cada decisão
        </h2>
        <p style="font-family:'Jost',sans-serif;font-weight:300;font-size:15px;line-height:1.9;color:rgba(244,242,238,0.6);margin-top:28px;">
          A ARQHAUS é constituída como Sociedade Empresária Limitada, com capital igualmente distribuído entre os cinco sócios-fundadores, todos arquitetos urbanistas formados e especialistas em suas áreas de atuação.
        </p>
        <p style="font-family:'Jost',sans-serif;font-weight:300;font-size:13px;line-height:1.8;color:rgba(244,242,238,0.4);margin-top:16px;">
          CNAE 7111-1/00 · 4322-3/02 · 4322-3/01 — Simples Nacional
        </p>
      </div>
      <div class="identity-cards reveal reveal-delay-2">
        <div class="identity-card">
          <div class="identity-card-icon">◈</div>
          <div class="identity-card-title">Responsabilidade</div>
          <p class="identity-card-text">Cada projeto é entregue com rigor técnico e cuidado irrestrito com prazos e orçamentos.</p>
        </div>
        <div class="identity-card">
          <div class="identity-card-icon">◎</div>
          <div class="identity-card-title">Ética</div>
          <p class="identity-card-text">Transparência e honestidade como base de cada relacionamento com clientes e parceiros.</p>
        </div>
        <div class="identity-card">
          <div class="identity-card-icon">◇</div>
          <div class="identity-card-title">Comprometimento</div>
          <p class="identity-card-text">Dedicação total da equipe desde a primeira reunião até a entrega das chaves.</p>
        </div>
        <div class="identity-card">
          <div class="identity-card-icon">◉</div>
          <div class="identity-card-title">Segurança</div>
          <p class="identity-card-text">Normas técnicas, acessibilidade e engenharia de segurança do trabalho em todos os projetos.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- TEAM -->
  <section class="team" id="equipe">
    <div class="team-header">
      <div class="section-tag reveal">A equipe</div>
      <h2 class="section-title reveal reveal-delay-1">
        Mentes <em>criativas</em><br>por trás de cada obra
      </h2>
    </div>
    <div class="team-grid">
      <div class="team-card reveal">
        <img class="team-photo"
          src="https://lh3.googleusercontent.com/pw/AP1GczOXF4itscuf5u0oZogDs4CeXjcDGmsNzVmOg914EzvNQMvwoB1k3grZ5II1ALgYhlseMchcIUbhoLW_tfVSpjKbZwblU-I_2Lilv9XvLM33gJ9gZb3gnCnfN-MOtU_V_U3UEHyHW0rgNYy6jGbXXqw=w655-h947-s-no?authuser=0"
          alt="Beatriz Deutsch">
        <div class="team-name">Beatriz Deutsch</div>
        <div class="team-role">Modelagem · Paisagismo · Luminotécnica</div>
      </div>
      <div class="team-card reveal reveal-delay-1">
        <img class="team-photo"
          src="https://lh3.googleusercontent.com/pw/AP1GczMzu0-1nBans7C1gNGCv8cwkfHDX_wexQEtlIdUdkM_JeJUO5YGrn1ofzokxX4uhVqSHtXCfbjwXKHMhpTSJbLnaIDI1ZG4CEQmtN1RjdsFJV0NKNUqo2IRdcOjUdEmXFibPHRILu70FPVfdp6cdbY=w511-h710-s-no?authuser=0"
          alt="Dhayana Muzzillo">
        <div class="team-name">Dhayana Muzzillo</div>
        <div class="team-role">HVAC · Gases Medicinais · Infraestrutura</div>
      </div>
      <div class="team-card reveal reveal-delay-2">
        <img class="team-photo"
          src="https://lh3.googleusercontent.com/pw/AP1GczOarYXZZAYoUnvavotXx6b_q69WTw9_uhvyB_f1j6cGnFtJUMsZ4v-HEgnGF88FTsywJ1nMWgkJuu_YAKtdYoiyjXXBJ7cwWHcTMM7-hiHsGuVHZYpeuDOED9zgabiPmxH61Fn3YyvJObLA78bhshA=w533-h947-s-no?authuser=0"
          alt="Gabriela Heckler">
        <div class="team-name">Gabriela Heckler</div>
        <div class="team-role">Design · Tendências · Gestão</div>
      </div>
      <div class="team-card reveal reveal-delay-3">
        <img class="team-photo"
          src="https://lh3.googleusercontent.com/pw/AP1GczPkxu1NZkBqjfubB7x5PVNQ0XZ4mnNXIZwra18f666uiFKxJnPxbxZaLJIknAVl41Ivkr3iUqhZfSxna3zfjlLLBZ-5CjBcuQxnny25Jzg15PVl2zx6fOz9efOf8IYRs3rBTgQ8ZilzWga4weZXZ4o=w744-h947-s-no?authuser=0"
          alt="Nariman Fayed">
        <div class="team-name">Nariman Fayed</div>
        <div class="team-role">Projetos 3D · Acessibilidade · Reforma</div>
      </div>
      <div class="team-card reveal reveal-delay-4">
        <img class="team-photo"
          src="https://img.freepik.com/fotos-gratis/jovem-barbudo-com-camisa-listrada_273609-5677.jpg?semt=ais_hybrid&w=740&q=80"
          alt="Vinicius Ronzoni">
        <div class="team-name">Vinicius Ronzoni</div>
        <div class="team-role">Revit · Feng Shui · Interiores</div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="contact" id="contato">
    <div class="contact-inner">
      <div class="contact-info reveal">
        <div class="section-tag">Fale conosco</div>
        <h2 class="section-title">
          Vamos criar algo <em>extraordinário</em>
        </h2>
        <p>
          Estamos prontos para transformar sua ideia em realidade. Entre em contato para uma consulta inicial sem compromisso.
        </p>
        <div class="contact-detail">
          <div class="contact-item">
            <div class="contact-item-icon">◎</div>
            <div>
              <div class="contact-item-label">Localização</div>
              <div class="contact-item-value">Foz do Iguaçu — Paraná, Brasil</div>
            </div>
          </div>
          <div class="contact-item">
            <div class="contact-item-icon">◈</div>
            <div>
              <div class="contact-item-label">E-mail</div>
              <div class="contact-item-value">contato@arqhaus.com.br</div>
            </div>
          </div>
          <div class="contact-item">
            <div class="contact-item-icon">◇</div>
            <div>
              <div class="contact-item-label">Registro</div>
              <div class="contact-item-value">CAU/BR — Arquitetura e Urbanismo</div>
            </div>
          </div>
        </div>
      </div>
      <div class="contact-form reveal reveal-delay-2">
        <div class="form-row">
          <div class="form-group">
            <label class="form-label">Nome</label>
            <input type="text" class="form-input" placeholder="Seu nome completo">
          </div>
          <div class="form-group">
            <label class="form-label">Telefone</label>
            <input type="tel" class="form-input" placeholder="(45) 99999-9999">
          </div>
        </div>
        <div class="form-group">
          <label class="form-label">E-mail</label>
          <input type="email" class="form-input" placeholder="seu@email.com">
        </div>
        <div class="form-group">
          <label class="form-label">Tipo de Projeto</label>
          <input type="text" class="form-input" placeholder="Residencial, Comercial, Reforma...">
        </div>
        <div class="form-group">
          <label class="form-label">Mensagem</label>
          <textarea class="form-textarea" placeholder="Descreva seu projeto..."></textarea>
        </div>
        <button class="form-btn">Enviar mensagem →</button>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-top">
      <div class="footer-brand">
        <div class="nav-logo" style="display:flex;align-items:center;gap:12px;">
          <div class="logo-mark" style="width:36px;">
            <svg viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M10 48 L30 12 L50 48" stroke="#f4f2ee" stroke-width="3" fill="none" stroke-linecap="square"/>
              <path d="M19 34 L41 34" stroke="#f4f2ee" stroke-width="3"/>
              <path d="M28 12 L28 20" stroke="#b8935a" stroke-width="2.5"/>
              <path d="M32 12 L32 20" stroke="#b8935a" stroke-width="2.5"/>
              <path d="M28 16 L32 16" stroke="#b8935a" stroke-width="2"/>
            </svg>
          </div>
          <span class="logo-wordmark">ARQHAUS</span>
        </div>
        <div class="footer-tagline">Arquitetura & Design — Foz do Iguaçu</div>
      </div>
      <div class="footer-links">
        <div class="footer-col">
          <div class="footer-col-title">Navegação</div>
          <ul>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#projetos">Projetos</a></li>
            <li><a href="#equipe">Equipe</a></li>
            <li><a href="#contato">Contato</a></li>
          </ul>
        </div>
        <div class="footer-col">
          <div class="footer-col-title">Serviços</div>
          <ul>
            <li><a href="#servicos">Projeto Arquitetônico</a></li>
            <li><a href="#servicos">Arquitetura de Interiores</a></li>
            <li><a href="#servicos">Conforto Ambiental</a></li>
            <li><a href="#servicos">Instalações Prediais</a></li>
            <li><a href="#servicos">Paisagismo</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="footer-copy">© 2024 ARQHAUS — Todos os direitos reservados.</div>
      <div class="footer-cnae">
        CNAE 7111-1/00 · 4322-3/02 · 4322-3/01<br>
        Sociedade Empresária Limitada — Simples Nacional
      </div>
    </div>
  </footer>

  <script>
    // Custom cursor
    const cursor = document.getElementById('cursor');
    const ring = document.getElementById('cursorRing');
    let mx = 0, my = 0, rx = 0, ry = 0;
    document.addEventListener('mousemove', e => {
      mx = e.clientX; my = e.clientY;
      cursor.style.left = mx + 'px';
      cursor.style.top = my + 'px';
    });
    (function animateRing() {
      rx += (mx - rx) * 0.12;
      ry += (my - ry) * 0.12;
      ring.style.left = rx + 'px';
      ring.style.top = ry + 'px';
      requestAnimationFrame(animateRing);
    })();
    document.querySelectorAll('a, button').forEach(el => {
      el.addEventListener('mouseenter', () => {
        ring.style.width = '50px'; ring.style.height = '50px';
        ring.style.borderColor = 'rgba(184,147,90,0.8)';
      });
      el.addEventListener('mouseleave', () => {
        ring.style.width = '32px'; ring.style.height = '32px';
        ring.style.borderColor = 'rgba(184,147,90,0.5)';
      });
    });

    // Navbar scroll
    const navbar = document.getElementById('navbar');
    window.addEventListener('scroll', () => {
      navbar.classList.toggle('scrolled', window.scrollY > 60);
    });

    // Reveal on scroll
    const reveals = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); } });
    }, { threshold: 0.1 });
    reveals.forEach(el => observer.observe(el));
  </script>
</body>
</html>
