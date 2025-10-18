<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Calculatrice — Jules Nemie</title>
  <meta name="description" content="Calculatrice web moderne par Jules Nemie. Fonctions de base, design responsive, accès clavier." />
  <style>
    :root{
      --bg:#0f172a;           /* slate-900 */
      --panel:#111827;        /* gray-900 */
      --key:#1f2937;          /* gray-800 */
      --key-muted:#0b1220;    /* darker */
      --text:#e5e7eb;         /* gray-200 */
      --muted:#94a3b8;        /* slate-400 */
      --accent:#22d3ee;       /* cyan-400 */
      --accent-2:#60a5fa;     /* blue-400 */
      --danger:#ef4444;       /* red-500 */
      --ring:rgba(34,211,238,.35);
      --shadow:0 20px 60px -20px rgba(2,8,23,.6);
    }
    *{box-sizing:border-box}
    html,body{margin:0;background:radial-gradient(1200px 600px at 10% -10%,rgba(34,211,238,.08),transparent),radial-gradient(1000px 600px at 110% 10%,rgba(96,165,250,.08),transparent),var(--bg);color:var(--text);font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Arial;line-height:1.4}
    a{color:var(--accent)}
    .container{max-width:900px;margin:0 auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:16px}
    .brand{font-weight:800;letter-spacing:.4px}
    .github{padding:8px 12px;border-radius:12px;border:1px solid rgba(148,163,184,.2);background:linear-gradient(135deg,rgba(34,211,238,.12),rgba(96,165,250,.12))}

    /* Card */
    .calc{display:grid;grid-template-columns:1fr;gap:14px;background:linear-gradient(180deg,rgba(17,24,39,.9),rgba(17,24,39,.75));border:1px solid rgba(148,163,184,.18);border-radius:18px;padding:16px;box-shadow:var(--shadow)}

    /* Display */
    .display{background:linear-gradient(180deg,rgba(2,6,23,.85),rgba(2,6,23,.65));border:1px solid rgba(148,163,184,.2);border-radius:14px;padding:16px 14px}
    .expr{font-size:14px;color:var(--muted);min-height:20px;word-break:break-all}
    .result{font-variant-numeric:tabular-nums;font-size:clamp(28px,6vw,44px);font-weight:800;min-height:48px;word-break:break-all}

    /* Keys grid */
    .keys{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
    .key{user-select:none;display:inline-flex;align-items:center;justify-content:center;height:56px;border-radius:14px;border:1px solid rgba(148,163,184,.18);background:linear-gradient(180deg,var(--key),var(--key-muted));font-weight:700;cursor:pointer;transition:transform .06s ease, box-shadow .12s ease;}
    .key:focus{outline:none;box-shadow:0 0 0 4px var(--ring)}
    .key:hover{transform:translateY(-1px)}
    .key.op{background:linear-gradient(180deg,rgba(31,41,55,.9),rgba(31,41,55,.7))}
    .key.eq{background:linear-gradient(135deg,rgba(34,211,238,.18),rgba(96,165,250,.18));border-color:rgba(34,211,238,.4)}
    .key.danger{background:linear-gradient(180deg,rgba(239,68,68,.22),rgba(239,68,68,.12));border-color:rgba(239,68,68,.35)}
    .span-2{grid-column:span 2}

    footer{margin-top:22px;color:var(--muted);font-size:14px}

    @media(min-width:740px){
      .layout{display:grid;grid-template-columns:1.1fr .9fr;gap:18px}
      .panel{background:linear-gradient(180deg,rgba(17,24,39,.6),rgba(17,24,39,.4));border:1px solid rgba(148,163,184,.18);border-radius:18px;padding:14px}
      .panel h2{margin:6px 8px 10px;font-size:16px;color:var(--muted)}
      .panel ul{margin:0 8px 8px 22px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">Calculatrice — Jules&nbsp;Nemie</div>
      <a class="github" href="#" aria-label="Ouvrir le code sur GitHub (à remplacer)">Voir le code</a>
    </header>

    <div class="layout">
      <!-- CALCULATOR -->
      <section class="calc" aria-label="Calculatrice">
        <div class="display" role="group" aria-label="Affichage">
          <div class="expr" id="expr" aria-live="polite"></div>
          <div class="result" id="result" aria-live="polite">0</div>
        </div>
        <div class="keys" role="group" aria-label="Clavier de calculatrice">
          <button class="key danger" data-action="clear" aria-label="Effacer tout (C)">C</button>
          <button class="key danger" data-action="back" aria-label="Supprimer un caractère (⌫)">⌫</button>
          <button class="key op" data-value="%" aria-label="Pourcentage">%</button>
          <button class="key op" data-value="/" aria-label="Division">÷</button>

          <button class="key" data-value="7">7</button>
          <button class="key" data-value="8">8</button>
          <button class="key" data-value="9">9</button>
          <button class="key op" data-value="*" aria-label="Multiplication">×</button>

          <button class="key" data-value="4">4</button>
          <button class="key" data-value="5">5</button>
          <button class="key" data-value="6">6</button>
          <button class="key op" data-value="-" aria-label="Soustraction">−</button>

          <button class="key" data-value="1">1</button>
          <button class="key" data-value="2">2</button>
          <button class="key" data-value="3">3</button>
          <button class="key op" data-value="+" aria-label="Addition">+</button>

          <button class="key span-2" data-value="0">0</button>
          <button class="key" data-value=".">.</button>
          <button class="key eq" data-action="equals" aria-label="Égal">=</button>
        </div>
      </section>

      <!-- SIDE PANEL: SHORTCUTS & TIPS -->
      <aside class="panel" aria-label="Raccourcis et astuces">
        <h2>Raccourcis clavier</h2>
        <ul>
          <li>Chiffres 0–9</li>
          <li>Opérateurs : + − × ÷ (utiliser <kbd>*</kbd> et <kbd>/</kbd> au clavier)</li>
          <li><kbd>Backspace</kbd> : supprimer</li>
          <li><kbd>Enter</kbd> : calculer</li>
          <li><kbd>Esc</kbd> : effacer</li>
        </ul>
        <h2>Astuce</h2>
        <ul>
          <li>Le symbole % renvoie un pourcentage simple (ex. 50% de 120 ⇒ 60).</li>
        </ul>
      </aside>
    </div>

    <footer>
      <small>© <span id="year"></span> Jules Nemie — Projet calculatrice. Design responsive, accessible et prêt pour GitHub Pages.</small>
    </footer>
  </div>

  <script>
    // Helpers
    const $ = sel => document.querySelector(sel);
    const exprEl = $('#expr');
    const resEl = $('#result');

    function setYear(){ document.getElementById('year').textContent = new Date().getFullYear(); }

    // State
    let expression = '';

    // Percent handling: convert "a%b" when appropriate to (a*b/100)
    function sanitize(input){
      // allow only digits, operators, dot, parentheses, spaces and %
      let s = input.replace(/[^0-9+\-*/().% ]/g, '');
      // Replace occurrences like "a%b" with (a*b/100)
      s = s.replace(/(\d+(?:\.\d+)?)%\s*(\d+(?:\.\d+)?)/g, '($1*$2/100)');
      // Also handle trailing percent like "50%" => (50/100)
      s = s.replace(/(\d+(?:\.\d+)?)%/g, '($1/100)');
      return s;
    }

    function calculate(){
      if(!expression) return;
      try{
        const s = sanitize(expression);
        // eslint-disable-next-line no-new-func
        let val = Function('return (' + s + ')')();
        if (typeof val === 'number' && isFinite(val)) {
          resEl.textContent = formatNumber(val);
        } else {
          resEl.textContent = 'Erreur';
        }
      }catch(e){
        resEl.textContent = 'Erreur';
      }
    }

    function formatNumber(n){
      const str = Math.round((n + Number.EPSILON) * 1e12) / 1e12; // limit precision
      return new Intl.NumberFormat('fr-FR').format(str);
    }

    function pressValue(v){
      expression += String(v);
      exprEl.textContent = expression;
    }

    function back(){
      expression = expression.slice(0, -1);
      exprEl.textContent = expression;
    }

    function clearAll(){
      expression = '';
      exprEl.textContent = '';
      resEl.textContent = '0';
    }

    function equals(){
      calculate();
      // After showing the result, make it the new expression for chaining
      expression = resEl.textContent.replace(/\s/g, '');
      // if result is not a number (Erreur), reset expression
      if (expression === 'Erreur') expression = '';
      exprEl.textContent = expression;
    }

    function handleClick(e){
      const t = e.target.closest('button.key');
      if(!t) return;
      const val = t.dataset.value;
      const action = t.dataset.action;
      if(action === 'clear') return clearAll();
      if(action === 'back') return back();
      if(action === 'equals') return equals();
      if(val) pressValue(val);
    }

    function handleKey(e){
      const k = e.key;
      if(/^[0-9]$/.test(k)) return pressValue(k);
      if(['+','-','*','/','.','(',')','%'].includes(k)) return pressValue(k);
      if(k === 'Enter' || k === '=') return equals();
      if(k === 'Backspace') return back();
      if(k === 'Escape') return clearAll();
    }

    document.addEventListener('click', handleClick);
    document.addEventListener('keydown', handleKey);
    setYear();
  </script>
</body>
</html>
