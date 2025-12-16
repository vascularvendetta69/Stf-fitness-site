# Stf-fitness-site
Homepage
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>STF Fitness – Online Coaching</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style >
    :root {
      --bg: #0f0f10;
      --card: #18181b;
      --accent: #f97316;
      --accent-soft: rgba(249,115,22,0.2);
      --text: #f9fafb;
      --muted: #9ca3af;
      --border: #27272f;
      --radius: 12px;
      --font: system-ui, -apple-system, BlinkMacSystemFont, "SF Pro Text",
              "Segoe UI", sans-serif;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      padding: 0;
      font-family: var(--font);
      background: radial-gradient(circle at top, #1f2937 0, #020617 50%, #000 100%);
      color: var(--text);
    }

    .page {
      max-width: 1000px;
      margin: 0 auto;
      padding: 24px 16px 48px;
    }

    header {
      text-align: center;
      margin-bottom: 24px;
    }

    .logo {
      width: 140px;
      height: auto;
      display: block;
      margin: 0 auto 12px auto;
      border-radius: 999px;
      border: 2px solid var(--accent);
      padding: 6px;
      background: #020617;
      object-fit: contain;
    }

    .brand-name {
      font-size: 1.6rem;
      font-weight: 700;
      letter-spacing: 0.12em;
      text-transform: uppercase;
    }

    .brand-tag {
      font-size: 0.95rem;
      color: var(--muted);
    }

    nav {
      margin-top: 10px;
      font-size: 0.9rem;
    }

    nav a {
      color: var(--muted);
      text-decoration: none;
      margin: 0 8px;
    }

    nav a:hover { color: var(--accent); }

    .hero-card {
      background: rgba(12, 12, 16, 0.96);
      border-radius: 18px;
      border: 1px solid var(--border);
      box-shadow: 0 18px 45px rgba(0, 0, 0, 0.75);
      padding: 26px 20px 28px;
      backdrop-filter: blur(14px);
      margin-bottom: 20px;
      text-align: center;
    }

    @media (min-width: 768px) {
      .hero-card { padding: 32px 40px 34px; }
    }

    .hero-title {
      font-size: 1.8rem;
      margin-bottom: 8px;
    }

    .hero-subtitle {
      font-size: 0.98rem;
      color: var(--muted);
      max-width: 640px;
      margin: 0 auto 16px;
    }

    .hero-cta { margin-top: 16px; }

    .cta-btn {
      display: inline-block;
      padding: 11px 26px;
      border-radius: 999px;
      background: linear-gradient(to right, #f97316, #ea580c);
      color: #0b0b0b;
      font-weight: 600;
      font-size: 0.95rem;
      text-decoration: none;
      box-shadow: 0 10px 30px rgba(249,115,22,0.45);
    }

    .cta-btn:hover {
      filter: brightness(1.05);
      transform: translateY(-1px);
    }

    .cta-btn:active {
      transform: translateY(0);
      box-shadow: 0 5px 16px rgba(0, 0, 0, 0.8);
    }

    .pill {
      display: inline-block;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(15,23,42,0.8);
      border: 1px solid var(--border);
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--muted);
      margin-bottom: 8px;
    }

    .grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 16px;
      margin-bottom: 16px;
    }

    @media (min-width: 850px) {
      .grid { grid-template-columns: 2fr 3fr; }
    }

    .card {
      background: rgba(8, 8, 12, 0.96);
      border-radius: 16px;
      border: 1px solid var(--border);
      padding: 18px 16px 20px;
    }

    .card h2 {
      font-size: 1.1rem;
      margin-top: 0;
      margin-bottom: 8px;
    }

    .card p {
      font-size: 0.9rem;
      color: var(--muted);
      line-height: 1.5;
    }

    .card ul {
      padding-left: 18px;
      margin: 6px 0 0;
    }

    .card li {
      font-size: 0.9rem;
      color: var(--muted);
      margin-bottom: 4px;
    }

    .highlight {
      color: var(--accent);
      font-weight: 600;
    }

    .mission-image {
  width: 60%;
  height: auto;
  margin: 16px auto 0;
  display: block;
  border-radius: 12px;
  border: 1px solid var(--border);
    }

    .footer {
      margin-top: 20px;
      font-size: 0.8rem;
      color: var(--muted);
      text-align: center;
    }

    .footer a {
      color: var(--muted);
      text-decoration: none;
    }

    .footer a:hover { color: var(--accent); }
  </style>
</head>
<body>
  <div class="page">
    <header>
      <!-- Logo clickable to Instagram -->
      <a href="https://instagram.com/stronger_than_fu" target="_blank">
        <img src="https://i.imgur.com/2gEg9gA.jpeg" alt="STF Fitness Logo" class="logo" />
      </a>
      <div class="brand-name">STF FITNESS</div>
      <div class="brand-tag">@stronger_than_fu</div>
      <nav>
        <a href="index.html">Home</a> •
        <a href="intakeform.html">Apply for Coaching</a>
      </nav>
    </header>

    <!-- HERO -->
    <section class="hero-card">
      <div class="pill">Online Coaching</div>
      <h1 class="hero-title">STF Fitness Coaching</h1>
      <p class="hero-subtitle">
        Structured training, clear nutrition, and honest guidance so you can finally
        build a strong, lean, healthy body without guesswork.
      </p>
      <div class="hero-cta">
        <a href="intakeform.html" class="cta-btn">Apply for Coaching</a>
      </div>
    </section>

    <!-- ABOUT + MISSION -->
    <section class="grid">
      <!-- ABOUT -->
      <div class="card">
        <h2>About Me</h2>
        <p>
          I’m Brad, the coach behind <span class="highlight">STF Fitness</span>.
          A few years ago, I was 360 lbs and stuck in the same cycle most people fall into:
          overeating, no structure, and a lifestyle that was destroying my confidence.
        </p>
        <p>
          I decided to take control. I educated myself on nutrition, training, metabolism,
          and behavior change — and through disciplined execution, I dropped
          <span class="highlight">150 lbs in one year</span>, entirely through my own
          self-education and application.
        </p>
        <p>
          More recently, I’ve taken things further by working directly with a
          <span class="highlight">high-level prep coach</span> to learn how real progress
          and muscle gain are achieved at an elite level.
        </p>
        <p>
          Because of that experience, my clients get access to the same principles, structure,
          and systems used by high-level athletes.
        </p>
        <p>
          I’m a Red Seal tradesman and a coach who believes in clarity, structure, and results.
          My goal is to guide you with the same education and systems that changed my own life.
        </p>
      </div>

      <!-- MISSION + TRANSFORMATION PHOTO -->
      <div class="card">
        <h2>Mission</h2>
        <p>
          <span class="highlight">STF Fitness</span> exists to create structure, discipline,
          and long-term physical change for real people.
        </p>
        <ul>
          <li>Cut through the noise of mainstream fitness trends</li>
          <li>Teach you how to properly fuel your body, not just “diet”</li>
          <li>Build strength, muscle, and confidence that actually lasts</li>
          <li>Make your plan simple, sustainable, and suited to your real life</li>
          <li>Educate you so you never have to guess again</li>
        </ul>

        <!-- Transformation Picture -->
        <img
          src="https://i.imgur.com/Fi0AYmk.jpeg"
          alt="Brad Transformation"
          class="mission-image"
        />
      </div>
    </section>

    <!-- WHO I WORK WITH + WHAT YOU GET -->
    <section class="grid">
      <div class="card">
        <h2>Who I Work With</h2>
        <ul>
          <li>People tired of starting over every Monday</li>
          <li>Men and women who want to lose fat the right way</li>
          <li>Busy workers (especially trades and shift work) who need structure</li>
          <li>Beginners who want clear guidance and a simple plan</li>
          <li>Lifters who want real progress: more muscle, less fat, better performance</li>
        </ul>
      </div>

      <div class="card">
        <h2>What You Get</h2>
        <ul>
          <li>Personalized training plan (gym or home-based)</li>
          <li>Custom nutrition targets and meal structure</li>
          <li>Weekly check-ins with real adjustments</li>
          <li>Exercise form feedback and guidance</li>
          <li>Accountability and straightforward communication</li>
          <li>Education so you understand why the plan works</li>
        </ul>
      </div>
    </section>

    <!-- ENCOURAGEMENT / CTA -->
    <section class="card">
      <h2>Ready to Stop Guessing?</h2>
      <p>
        You don’t need another fad diet or quick fix.
        You need structure, consistency, and a plan built around your real life.
      </p>
      <p>
        I’ve been where you are. I know what it feels like to want change but not
        have a clear path. If you’re ready to do the work, I’ll meet you there with
        a clear plan and honest feedback.
      </p>
      <p>
        If you’re serious about changing your body and your habits, click below and apply.
        I review every application personally.
      </p>
      <div style="margin-top: 10px;">
        <a href="intakeform.html" class="cta-btn">Apply for no obligation consultation</a>
      </div>
    </section>

    <div class="footer">
     <div class="footer-line">
      STF Fitness • <a href="https://instagram.com/stronger_than_fu" target="_blank">@stronger_than_fu
       </a>
     </div>

  <div class="footer-line sub">
      My Personal Journey • <a href="https://instagram.com/vascular_vendetta_69" target="_blank">@vascular_vendetta_69
      </a>
    </div>
  </div>
 
