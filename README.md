# my-first-repo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mugundh — Virtual Reality on the Web</title>

  <!-- A-Frame (simple WebXR framework) -->
  <script src="https://aframe.io/releases/1.4.0/aframe.min.js"></script>

  <style>
    :root{
      --accent:#7c4dff;
      --bg:#0f1020;
      --card:#11121b;
      --glass: rgba(255,255,255,0.03);
    }
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color: #e6e6ff;
      background: linear-gradient(180deg, #07070b 0%, #0f1020 60%);
      -webkit-font-smoothing:antialiased;
    }
    header{
      padding:28px;
      display:flex;
      gap:18px;
      align-items:center;
    }
    .brand{
      font-weight:700;
      font-size:22px;
      color:var(--accent);
      letter-spacing:0.4px;
    }
    .subtitle{ color:#bfc1ff; opacity:0.9 }
    main{ padding:20px; max-width:980px; margin:0 auto; }
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:10px;
      padding:18px;
      margin-bottom:18px;
      box-shadow: 0 6px 25px rgba(10,10,30,0.5);
    }
    h1{ margin:0 0 6px 0; font-size:28px; }
    h2{ margin:12px 0; font-size:20px; color:var(--accent) }
    p{ line-height:1.5; color:#d6d7ff }
    .flex{ display:flex; gap:12px; flex-wrap:wrap; }
    .img-wrap{ flex:1 1 46%; min-width:260px; }
    img{ width:100%; border-radius:8px; display:block; }
    .vocab li{ margin:8px 0; }
    footer{ text-align:center; padding:28px; color:#9fa2d8; font-size:14px }
    .demo {
      height:420px;
      border-radius:10px;
      overflow:hidden;
    }
    .small-note{ font-size:13px; color:#aeb0d8 }
    /* Easter egg: press "g" to toggle mascot */
    #mascot{ display:none; position:fixed; right:18px; bottom:18px; width:120px; opacity:0.95; }
  </style>
</head>
<body>
  <header>
    <div>
      <div class="brand">Mugundh</div>
      <div class="subtitle">Virtual Reality on the Web • Project site</div>
    </div>
  </header>

  <main>
    <!-- Intro -->
    <section class="card">
      <h1>Virtual Reality on the Web (WebXR)</h1>
      <p>
        This page explains how VR &amp; AR can be delivered through web browsers using the WebXR APIs and friendly frameworks like A-Frame, Three.js, or Babylon.js.
        Visitors can try a tiny WebXR demo below (works on compatible browsers; desktop falls back to a 3D scene). 
      </p>
      <p class="small-note">
        Tip: For real VR on a headset like Meta Quest, open this page inside the headset browser (or a compatible mobile browser) and click <em>Enter VR</em>.
      </p>
    </section>

    <!-- What I want to do after high school (editable) -->
    <section class="card">
      <h2>My plans after high school</h2>
      <p><strong>(Replace this text with your own answer)</strong> — I plan to study <em>computer science / web development / game design / immersive tech</em> and build interactive web experiences that run in VR and AR.</p>
    </section>

    <!-- Researched Topic: Virtual Reality on the Web -->
    <section class="card">
      <h2>Quick researched summary</h2>
      <p>
        <strong>WebXR</strong> is the browser API that enables VR and AR experiences on the web so users can access immersive content without downloading apps. Developers often use WebXR together with 3D engines such as A-Frame, Three.js or Babylon.js to create interactive scenes. WebXR samples and tools are provided by the Immersive Web Working Group and docs like MDN and web.dev explain how to build demos and enter imm:contentReference[oaicite:1]{index=1}
