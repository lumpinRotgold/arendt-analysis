<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arendt Geopolitische Muster - Dramatische Analyse</title>
    <style>
        body {
            font-family: 'Georgia', 'Times New Roman', serif;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 800"><defs><radialGradient id="redGlow" cx="50%" cy="30%" r="70%"><stop offset="0%" style="stop-color:%23ff4444;stop-opacity:0.8"/><stop offset="50%" style="stop-color:%23cc2222;stop-opacity:0.6"/><stop offset="100%" style="stop-color:%23330000;stop-opacity:1"/></radialGradient></defs><rect width="100%" height="100%" fill="url(%23redGlow)"/><rect x="200" y="300" width="800" height="200" fill="%23441111" opacity="0.7"/><polygon points="400,200 500,150 600,200 550,250 450,250" fill="%23ff6666" opacity="0.4"/><circle cx="600" cy="150" r="80" fill="none" stroke="%23ffaa00" stroke-width="3" opacity="0.6"/></svg>') center/cover no-repeat fixed, 
                     linear-gradient(135deg, #1a0000, #440000, #1a0000);
            padding: 30px 20px;
            margin: 0;
            line-height: 1.6;
            color: #ffffff;
            min-height: 100vh;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: linear-gradient(135deg, rgba(0,0,0,0.9), rgba(68,0,0,0.8), rgba(0,0,0,0.9));
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(255,68,68,0.3), inset 0 0 50px rgba(255,136,136,0.1);
            border: 2px solid #ff4444;
            backdrop-filter: blur(10px);
        }
        
        .header {
            text-align: center;
            margin-bottom: 35px;
            padding-bottom: 25px;
            border-bottom: 3px solid #ff6666;
            background: linear-gradient(135deg, rgba(255,68,68,0.2), rgba(204,34,34,0.2));
            border-radius: 10px;
            padding: 25px;
        }
        
        .title {
            font-size: 2.2em;
            color: #ffdd44;
            margin-bottom: 10px;
            font-weight: bold;
            text-shadow: 0 0 20px #ffaa00, 0 0 40px #ff6600;
            letter-spacing: 2px;
        }
        
        .subtitle {
            font-size: 1.3em;
            color: #ffcccc;
            font-style: italic;
            text-shadow: 0 0 10px #ff8888;
        }
        
        .intro {
            background: linear-gradient(135deg, rgba(255,255,255,0.1), rgba(255,204,204,0.05));
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 30px;
            border-left: 5px solid #ffdd44;
            font-size: 1.1em;
            color: #ffeeee;
            text-shadow: 0 1px 3px rgba(0,0,0,0.5);
        }
        
        .section {
            background: linear-gradient(135deg, rgba(255,255,255,0.1), rgba(0,0,0,0.3));
            padding: 25px;
            margin: 25px 0;
            border-radius: 12px;
            border-left: 5px solid;
            backdrop-filter: blur(5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.4);
        }
        
        .peace-section {
            border-left-color: #00ff88;
            background: linear-gradient(135deg, rgba(0,255,136,0.15), rgba(0,100,50,0.2));
            box-shadow: 0 0 30px rgba(0,255,136,0.2), 0 8px 25px rgba(0,0,0,0.4);
        }
        
        .fortress-section {
            border-left-color: #ff3366;
            background: linear-gradient(135deg, rgba(255,51,102,0.15), rgba(100,0,25,0.2));
            box-shadow: 0 0 30px rgba(255,51,102,0.2), 0 8px 25px rgba(0,0,0,0.4);
        }
        
        .critical-section {
            border-left-color: #ffaa00;
            background: linear-gradient(135deg, rgba(255,170,0,0.15), rgba(100,50,0,0.2));
            box-shadow: 0 0 30px rgba(255,170,0,0.2), 0 8px 25px rgba(0,0,0,0.4);
        }
        
        .section-title {
            font-size: 1.4em;
            font-weight: bold;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            text-shadow: 0 0 15px currentColor;
        }
        
        .peace-section .section-title {
            color: #00ff88;
        }
        
        .fortress-section .section-title {
            color: #ff3366;
        }
        
        .critical-section .section-title {
            color: #ffaa00;
        }
        
        .example-list {
            list-style: none;
            padding: 0;
        }
        
        .example-item {
            background: rgba(255,255,255,0.05);
            margin: 12px 0;
            padding: 15px;
            border-radius: 8px;
            border-left: 3px solid currentColor;
            backdrop-filter: blur(3px);
            transition: all 0.3s ease;
        }
        
        .example-item:hover {
            background: rgba(255,255,255,0.1);
            transform: translateX(5px);
        }
        
        .peace-section .example-item {
            border-left-color: #00ff88;
            color: #ccffee;
        }
        
        .fortress-section .example-item {
            border-left-color: #ff3366;
            color: #ffccdd;
        }
        
        .critical-section .example-item {
            border-left-color: #ffaa00;
            color: #ffeecc;
        }
        
        .example-title {
            font-weight: bold;
            font-size: 1.1em;
            margin-bottom: 5px;
            text-shadow: 0 1px 3px rgba(0,0,0,0.5);
        }
        
        .example-desc {
            font-size: 0.95em;
            opacity: 0.9;
            line-height: 1.5;
        }
        
        .emoji {
            font-size: 1.3em;
            margin-right: 12px;
            filter: drop-shadow(0 0 5px currentColor);
        }
        
        .quote {
            background: linear-gradient(135deg, rgba(0,0,0,0.6), rgba(68,0,0,0.4));
            border: 1px solid #ff6666;
            border-radius: 8px;
            padding: 15px;
            margin: 15px 0;
            font-style: italic;
            color: #ffdddd;
            text-shadow: 0 1px 3px rgba(0,0,0,0.7);
            position: relative;
        }
        
        .quote::before {
            content: '"';
            font-size: 3em;
            position: absolute;
            top: -15px;
            left: 10px;
            color: #ffaa00;
            text-shadow: 0 0 10px #ff6600;
        }
        
        .source {
            text-align: right;
            margin-top: 10px;
            font-size: 0.9em;
            color: #ffaaaa;
        }
        
        .glow-text {
            text-shadow: 0 0 10px currentColor, 0 0 20px currentColor, 0 0 30px currentColor;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="title glow-text">⚔️ ARENDT'S GEOPOLITISCHE MUSTER ⚔️</div>
            <div class="subtitle">Friedenspfad vs. Festungsstaat - Historische Beispiele</div>
        </div>
        
        <div class="intro">
            Basierend auf Arendts analytischem Rahmen von 1944, wo sie zwischen dem <strong class="glow-text" style="color: #00ff88;">"Friedenspfad"</strong> (regionale Integration) und dem <strong class="glow-text" style="color: #ff3366;">"Festungspfad"</strong> (militärische Dominanz durch externe Unterstützung) unterschied, lassen sich ähnliche Muster in verschiedenen geopolitischen Kontexten erkennen:
        </div>
        
        <div class="section peace-section">
            <div class="section-title">
                <span class="emoji">🇦</span>
                <span class="glow-text">Friedenspfad-Beispiele (Regionale Integration)</span>
            </div>
            <ul class="example-list">
                <li class="example-item">
                    <div class="example-title">Deutschland nach 1945</div>
                    <div class="example-desc">Von der Besatzung zur europäischen Integration durch EU/NATO-Mitgliedschaft</div>
                </li>
                <li class="example-item">
                    <div class="example-title">Südafrika nach 1994</div>
                    <div class="example-desc">Vom Apartheid-Staat zur regionalen Integration durch Wahrheits- und Versöhnungskommission</div>
                </li>
                <li class="example-item">
                    <div class="example-title">Irland/Nordirland</div>
                    <div class="example-desc">Good Friday Agreement (1998) beendete den "Festungsstatus"</div>
                </li>
            </ul>
        </div>
        
        <div class="section fortress-section">
            <div class="section-title">
                <span class="emoji">⚔️</span>
                <span class="glow-text">Festungspfad-Beispiele (Externe Abhängigkeit)</span>
            </div>
            <ul class="example-list">
                <li class="example-item">
                    <div class="example-title">Taiwan</div>
                    <div class="example-desc">Militärisch abhängig von US-Waffenlieferungen gegenüber China</div>
                </li>
                <li class="example-item">
                    <div class="example-title">Südkorea (bis 1980er)</div>
                    <div class="example-desc">Militärdiktatur gestützt durch massive US-Präsenz</div>
                </li>
                <li class="example-item">
                    <div class="example-title">Südvietnam (1954-1975)</div>
                    <div class="example-desc">Kollaps nach Ende der US-Unterstützung</div>
                </li>
            </ul>
        </div>
        
        <div class="section critical-section">
            <div class="section-title">
                <span class="emoji">💥</span>
                <span class="glow-text">Arendts Kernkritik bestätigt sich wenn:</span>
            </div>
            <ul class="example-list">
                <li class="example-item">
                    <div class="example-desc">Externe Militärhilfe zur Existenzgrundlage wird</div>
                </li>
                <li class="example-item">
                    <div class="example-desc">Regionale Nachbarn zu permanenten Feinden erklärt werden</div>
                </li>
                <li class="example-item">
                    <div class="example-desc">Innenpolitik von Sicherheitslogik dominiert wird</div>
                </li>
            </ul>
            
            <div class="quote">
                Arab enmity and force Israel to depend on U.S. support for its survival
                <div class="source">— The Menorah Journal</div>
            </div>
        </div>
    </div>
</body>
</html>
