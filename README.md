<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Malak — Music</title>
  <meta name="description" content="Malak — dreamy, atmospheric songs. Sleeps, Lullaby to Venus, Stamina, Shellshock." />
  <style>
    :root{
      --bg:#0a0a0a; --fg:#f5f5f5; --muted:#b7b7b7; --accent:#ffd45e; --card:#121212; --line:#222;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; background:var(--bg); color:var(--fg);
      font:16px/1.55 system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial,sans-serif;
      letter-spacing:.1px;
    }
    .wrap{max-width:960px; margin:0 auto; padding:24px 16px 56px}
    header{
      padding:56px 0 24px; text-align:center;
      border-bottom:1px solid var(--line);
      background:linear-gradient(180deg, rgba(255,212,94,.08), transparent 55%);
    }
    h1{margin:0; font-size:clamp(34px,6vw,64px); letter-spacing:.02em}
    h1 em{font-style:normal; color:var(--accent)}
    h2{margin:28px 0 12px; font-size:clamp(18px,3.2vw,26px)}
    p.sub{margin:8px 0 0; color:var(--muted)}
    .track{
      background:var(--card); border:1px solid var(--line);
      padding:14px; border-radius:12px; margin:14px 0 18px;
    }
    .track strong{display:block; margin-bottom:8px; font-size:18px}
    audio{width:100%; height:38px}
    details{
      margin-top:10px; background:#0e0e0e; border:1px dashed var(--line);
      border-radius:10px; padding:8px 10px;
    }
    details summary{cursor:pointer; color:var(--accent); font-weight:700}
    pre{
      white-space:pre-wrap; margin:8px 0 0;
      color:#e9e9e9; font:14px/1.6 ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;
    }
    .note{
      border-top:1px solid var(--line); margin-top:28px; padding-top:18px; color:var(--muted)
    }
    .phone{
      display:inline-block; margin-top:6px; padding:8px 12px;
      border:1px solid var(--line); border-radius:10px;
      color:var(--fg); background:#0f0f0f; text-decoration:none;
    }
    .phone:hover{box-shadow:0 0 0 2px rgba(255,212,94,.25) inset}
    footer{margin-top:26px; text-align:center; color:#9a9a9a; font-size:12px}
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <h1>Malak <em>— Music</em></h1>
      <p class="sub">Dreamy • atmospheric • ethereal</p>
    </div>
  </header>

  <main class="wrap">
    <h2>Listen</h2>

    <!-- 01 — Sleeps -->
    <section class="track">
      <strong>01 — Sleeps</strong>
      <audio controls preload="none">
        <!-- Put the file at /tracks/sleeps.wav (and optional mp3 fallback) -->
        <source src="tracks/sleeps.wav" type="audio/wav" />
        <source src="tracks/sleeps.mp3" type="audio/mpeg" />
        Your browser doesn’t support the audio element.
      </audio>
      <details>
        <summary>Lyrics — “Sleeps”</summary>
        <pre>I am nothing but a looser of a daughter
Saving words on a paper cut so thin
I’ll gladly save your prom
