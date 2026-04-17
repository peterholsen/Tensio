<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<title>TensioLog 2026</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600&family=DM+Mono:wght@400;500&display=swap');
:root{--green:#1a7a5e;--green-light:#e8f5f1;--amber:#b8620a;--amber-light:#fdf0e0;--red:#c0392b;--bg:#f4f2ed;--card:#ffffff;--text:#1a1a18;--muted:#6b6b64;--border:#ddddd5;--radius:16px;--radius-sm:10px}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
body{font-family:'DM Sans',sans-serif;background:var(--bg);color:var(--text);min-height:100vh}
.app{max-width:480px;margin:0 auto;padding:0 0 40px;min-height:100vh}
.header{background:var(--green);padding:48px 24px 24px;color:white}
.header-label{font-family:'DM Mono',monospace;font-size:11px;letter-spacing:2px;text-transform:uppercase;opacity:0.7;margin-bottom:4px}
.header-title{font-size:28px;font-weight:600;letter-spacing:-0.5px}
.header-sub{font-size:14px;opacity:0.75;margin-top:4px}
.progress-bar{display:flex;gap:4px;padding:16px 24px;background:var(--green)}
.prog-seg{height:3px;flex:1;border-radius:2px;background:rgba(255,255,255,0.25);transition:background 0.3s}
.prog-seg.done{background:rgba(255,255,255,0.9)}
.prog-seg.active{background:white}
.content{padding:24px}
.page{display:none}
.page.active{display:block}
.section-title{font-size:22px;font-weight:600;letter-spacing:-0.3px;margin-bottom:6px}
.section-sub{font-size:15px;color:var(--muted);margin-bottom:24px}
.dt-row{display:flex;gap:12px;margin-bottom:8px}
.dt-input{flex:1;padding:18px 14px;font-size:18px;font-family:'DM Mono',monospace;font-weight:500;border:1.5px solid var(--border);border-radius:var(--radius-sm);background:var(--card);color:var(--text);text-align:center;width:100%}
.dt-input:focus{outline:none;border-color:var(--green)}
.sensor-card{background:var(--card);border-radius:var(--radius);border:1.5px solid var(--border);padding:16px 18px;margin-bottom:12px;display:flex;align-items:center;gap:12px}
.sensor-info{flex:1}
.sensor-name{font-size:20px;font-weight:600;letter-spacing:-0.3px}
.sensor-depth{font-size:13px;color:var(--muted);margin-top:2px}
.stepper{display:flex;align-items:center;background:var(--bg);border-radius:var(--radius-sm);overflow:hidden;border:1.5px solid var(--border)}
.step-btn{width:56px;height:56px;font-size:30px;font-weight:300;border:none;background:transparent;color:var(--text);cursor:pointer;display:flex;align-items:center;justify-content:center;user-select:none;-webkit-user-select:none}
.step-btn:active{background:var(--border)}
.step-display{width:72px;height:56px;display:flex;align-items:center;justify-content:center;font-family:'DM Mono',monospace;font-size:22px;font-weight:500;border-left:1.5px solid var(--border);border-right:1.5px solid var(--border);background:var(--card);color:var(--text)}
.btn{width:100%;padding:20px;font-size:18px;font-weight:600;font-family:'DM Sans',sans-serif;border:none;border-radius:var(--radius);cursor:pointer;margin-top:12px;transition:transform 0.1s,opacity 0.1s;letter-spacing:-0.2px}
.btn:active{transform:scale(0.98);opacity:0.9}
.btn-primary{background:var(--green);color:white}
.btn-secondary{background:var(--card);color:var(--text);border:1.5px solid var(--border)}
.btn-no{background:var(--card);color:var(--muted);border:1.5px solid var(--border)}
.vol-card{background:var(--card);border-radius:var(--radius);border:1.5px solid var(--border);padding:20px 18px;margin-bottom:12px}
.vol-label{font-size:14px;color:var(--muted);margin-bottom:10px;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:1px}
.vol-row{display:flex;align-items:center;gap:12px}
.vol-input{flex:1;padding:16px;font-size:28px;font-family:'DM Mono',monospace;font-weight:500;border:1.5px solid var(--border);border-radius:var(--radius-sm);background:var(--bg);color:var(--text);text-align:center}
.vol-unit{font-size:20px;color:var(--muted);font-weight:500}
.summary-group{background:var(--card);border-radius:var(--radius);border:1.5px solid var(--border);overflow:hidden;margin-bottom:16px}
.summary-group-title{background:var(--green-light);padding:12px 18px;font-size:12px;font-family:'DM Mono',monospace;text-transform:uppercase;letter-spacing:1.5px;color:var(--green);font-weight:500}
.summary-row{display:flex;justify-content:space-between;align-items:center;padding:13px 18px;border-bottom:1px solid var(--border)}
.summary-row:last-child{border-bottom:none}
.summary-key{font-size:15px;color:var(--muted)}
.summary-val{font-family:'DM Mono',monospace;font-size:16px;font-weight:500;color:var(--text)}
.done-icon{width:80px;height:80px;background:var(--green);border-radius:50%;display:flex;align-items:center;justify-content:center;margin:32px auto 24px}
.done-icon svg{width:40px;height:40px;stroke:white;stroke-width:3;fill:none;stroke-linecap:round;stroke-linejoin:round}
.done-title{font-size:28px;font-weight:600;text-align:center;margin-bottom:8px}
.done-sub{font-size:15px;color:var(--muted);text-align:center;margin-bottom:32px;line-height:1.5;white-space:pre-line}
.loading-card{background:var(--card);border-radius:var(--radius);padding:32px 24px;text-align:center;border:1.5px solid var(--border);margin-top:24px}
.spinner{width:40px;height:40px;border:3px solid var(--border);border-top-color:var(--green);border-radius:50%;animation:spin 0.8s linear infinite;margin:0 auto 16px}
@keyframes spin{to{transform:rotate(360deg)}}
.loading-text{font-size:16px;color:var(--muted)}
.tag{display:inline-block;padding:4px 10px;border-radius:6px;font-size:12px;font-weight:500;font-family:'DM Mono',monospace;background:var(--green-light);color:var(--green);margin-bottom:16px}
.watering-added-info{background:var(--amber-light);border:1.5px solid #e8c88a;border-radius:var(--radius-sm);padding:14px 18px;font-size:15px;color:var(--amber);margin-bottom:16px;font-weight:500}
.error-card{background:#fdf0f0;border:1.5px solid #f5c0c0;border-radius:var(--radius-sm);padding:16px 18px;font-size:15px;color:var(--red);margin-top:16px;line-height:1.5}
.data-table{width:100%;border-collapse:collapse;font-size:13px;font-family:'DM Mono',monospace}
.data-table th{background:var(--green-light);color:var(--green);padding:8px 6px;text-align:center;font-size:11px;letter-spacing:1px}
.data-table td{padding:7px 6px;text-align:center;border-bottom:1px solid var(--border)}
.data-table tr:last-child td{border-bottom:none}
.tab-bar{display:flex;gap:8px;margin-bottom:20px}
.tab{flex:1;padding:12px;font-size:15px;font-weight:600;font-family:'DM Sans',sans-serif;border:1.5px solid var(--border);border-radius:var(--radius-sm);background:var(--card);color:var(--muted);cursor:pointer;text-align:center}
.tab.active{background:var(--green);color:white;border-color:var(--green)}
.download-btn{display:block;width:100%;padding:16px;font-size:16px;font-weight:600;font-family:'DM Sans',sans-serif;border:1.5px solid var(--green);border-radius:var(--radius);background:var(--green-light);color:var(--green);cursor:pointer;text-align:center;margin-bottom:12px;text-decoration:none}
</style>
</head>
<body>
<div class="app">
  <div class="header">
    <div class="header-label">Wolfenstein 2026</div>
    <div class="header-title">TensioLog</div>
    <div class="header-sub" id="header-sub">Loading...</div>
  </div>
  <div class="progress-bar">
    <div class="prog-seg active" id="prog-0"></div>
    <div class="prog-seg" id="prog-1"></div>
    <div class="prog-seg" id="prog-2"></div>
    <div class="prog-seg" id="prog-3"></div>
    <div class="prog-seg" id="prog-4"></div>
  </div>
  <div class="content">

    <!-- PAGE: DATE/TIME -->
    <div class="page active" id="page-dt">
      <div class="tab-bar">
        <div class="tab active" onclick="showTab('log')">Log reading</div>
        <div class="tab" onclick="showTab('data')">View data</div>
      </div>
      <div id="tab-log">
        <div class="section-title">New reading</div>
        <div class="section-sub">Confirm date and time</div>
        <div class="dt-row">
          <input class="dt-input" type="date" id="inp-date">
          <input class="dt-input" type="time" id="inp-time">
        </div>
        <button class="btn btn-primary" onclick="goToNorth()">Confirm →</button>
      </div>
      <div id="tab-data" style="display:none">
        <div class="section-title">Recent readings</div>
        <div class="section-sub" id="data-count"></div>
        <div id="data-table-container"></div>
        <a id="download-link" class="download-btn" download="TensioLog-2026.html">⬇ Download full file</a>
      </div>
    </div>

    <!-- PAGE: NORTH -->
    <div class="page" id="page-north">
      <div class="tag">Stack 1 of 3</div>
      <div class="section-title">North</div>
      <div class="section-sub">Adjust from last reading</div>
      <div id="sensors-north"></div>
      <button class="btn btn-primary" onclick="goTo('page-middle',2)">Next: Middle →</button>
      <button class="btn btn-no" onclick="goTo('page-dt',0)">← Back</button>
    </div>

    <!-- PAGE: MIDDLE -->
    <div class="page" id="page-middle">
      <div class="tag">Stack 2 of 3</div>
      <div class="section-title">Middle</div>
      <div class="section-sub">Adjust from last reading</div>
      <div id="sensors-middle"></div>
      <button class="btn btn-primary" onclick="goTo('page-crown',3)">Next: Crown →</button>
      <button class="btn btn-no" onclick="goTo('page-north',1)">← Back</button>
    </div>

    <!-- PAGE: CROWN -->
    <div class="page" id="page-crown">
      <div class="tag">Stack 3 of 3</div>
      <div class="section-title">Crown</div>
      <div class="section-sub">Adjust from last reading</div>
      <div id="sensors-crown"></div>
      <button class="btn btn-primary" onclick="goTo('page-watering',4)">Next: Watering →</button>
      <button class="btn btn-no" onclick="goTo('page-middle',2)">← Back</button>
    </div>

    <!-- PAGE: WATERING YES/NO -->
    <div class="page" id="page-watering">
      <div class="section-title">Watering event?</div>
      <div class="section-sub">Was there any irrigation?</div>
      <button class="btn btn-primary" onclick="goTo('page-watering-detail',4)">Yes — add event</button>
      <button class="btn btn-no" onclick="goTo('page-summary',4)">No — go to summary</button>
      <button class="btn btn-secondary" onclick="goTo('page-crown',3)">← Back</button>
    </div>

    <!-- PAGE: WATERING DETAIL -->
    <div class="page" id="page-watering-detail">
      <div class="section-title">Watering event</div>
      <div class="section-sub">When and how much?</div>
      <div id="watering-added-banner" style="display:none"></div>
      <div class="vol-card">
        <div class="vol-label">Date &amp; Time</div>
        <div class="dt-row" style="margin-bottom:0">
          <input class="dt-input" type="date" id="w-date">
          <input class="dt-input" type="time" id="w-time">
        </div>
      </div>
      <div class="vol-card">
        <div class="vol-label">Volume</div>
        <div class="vol-row">
          <input class="vol-input" type="number" id="w-vol" value="400" min="0" step="50">
          <div class="vol-unit">L</div>
        </div>
      </div>
      <button class="btn btn-primary" onclick="addWatering()">Add this event</button>
      <button class="btn btn-no" onclick="goTo('page-summary',4)">Done — go to summary</button>
    </div>

    <!-- PAGE: SUMMARY -->
    <div class="page" id="page-summary">
      <div class="section-title">Summary</div>
      <div class="section-sub">Review before saving</div>
      <div id="summary-content"></div>
      <button class="btn btn-primary" onclick="submitAll()">Save to GitHub</button>
      <button class="btn btn-secondary" onclick="goTo('page-dt',0)">Start over</button>
    </div>

    <!-- PAGE: SUBMITTING -->
    <div class="page" id="page-submitting">
      <div class="loading-card">
        <div class="spinner"></div>
        <div class="loading-text" id="submit-status">Saving...</div>
      </div>
    </div>

    <!-- PAGE: DONE -->
    <div class="page" id="page-done">
      <div class="done-icon"><svg viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"></polyline></svg></div>
      <div class="done-title">Saved!</div>
      <div class="done-sub" id="done-msg"></div>
      <button class="btn btn-primary" onclick="resetApp()">New reading</button>
    </div>

  </div>
</div>

<script>
// ── CONFIG ──────────────────────────────────────────────────────────────────
const GITHUB_USER  = 'peterholsen';
const GITHUB_REPO  = 'Tensio';
const GITHUB_FILE  = 'index.html';
const GITHUB_TOKEN = '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';
const API_BASE     = `https://api.github.com/repos/${GITHUB_USER}/${GITHUB_REPO}/contents/${GITHUB_FILE}`;

// ── EMBEDDED DATA ────────────────────────────────────────────────────────────
// Data is stored as JSON inside the HTML file itself
var TENSIO_DATA = {
  readings: [
    {"date":"2026-04-01","time":"06:00","N_15cm":6.0,"N_30cm":6.0,"M_15cm":6.5,"M_30cm":7.5,"M_45cm":7.5,"C_15cm":8.5,"C_20cm":7.5,"C_30cm":8.0,"C_45cm":11.0,"C_60cm":10.0},
    {"date":"2026-04-01","time":"18:40","N_15cm":6.5,"N_30cm":6.5,"M_15cm":7.0,"M_30cm":8.0,"M_45cm":8.0,"C_15cm":9.5,"C_20cm":7.5,"C_30cm":8.5,"C_45cm":11.0,"C_60cm":10.0},
    {"date":"2026-04-03","time":"12:20","N_15cm":6.5,"N_30cm":6.0,"M_15cm":7.0,"M_30cm":8.0,"M_45cm":6.5,"C_15cm":9.0,"C_20cm":7.5,"C_30cm":9.0,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-03","time":"13:20","N_15cm":6.5,"N_30cm":6.0,"M_15cm":6.5,"M_30cm":8.0,"M_45cm":6.5,"C_15cm":8.0,"C_20cm":6.5,"C_30cm":9.0,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-03","time":"13:50","N_15cm":6.5,"N_30cm":6.5,"M_15cm":6.5,"M_30cm":8.0,"M_45cm":6.5,"C_15cm":7.5,"C_20cm":5.5,"C_30cm":9.0,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-03","time":"14:20","N_15cm":6.5,"N_30cm":6.5,"M_15cm":6.0,"M_30cm":8.0,"M_45cm":7.0,"C_15cm":6.5,"C_20cm":4.0,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":10.5},
    {"date":"2026-04-03","time":"15:20","N_15cm":6.5,"N_30cm":6.0,"M_15cm":5.0,"M_30cm":8.0,"M_45cm":7.0,"C_15cm":6.0,"C_20cm":4.0,"C_30cm":9.0,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-03","time":"17:50","N_15cm":6.0,"N_30cm":6.0,"M_15cm":5.0,"M_30cm":7.0,"M_45cm":7.0,"C_15cm":6.0,"C_20cm":4.0,"C_30cm":8.5,"C_45cm":11.0,"C_60cm":10.6},
    {"date":"2026-04-03","time":"21:40","N_15cm":5.0,"N_30cm":5.0,"M_15cm":5.0,"M_30cm":6.5,"M_45cm":7.5,"C_15cm":6.0,"C_20cm":5.0,"C_30cm":8.0,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-04","time":"08:30","N_15cm":5.0,"N_30cm":5.0,"M_15cm":5.5,"M_30cm":6.5,"M_45cm":7.0,"C_15cm":7.0,"C_20cm":5.5,"C_30cm":7.5,"C_45cm":10.5,"C_60cm":10.0},
    {"date":"2026-04-04","time":"12:30","N_15cm":5.5,"N_30cm":5.0,"M_15cm":5.0,"M_30cm":6.5,"M_45cm":6.5,"C_15cm":7.0,"C_20cm":6.0,"C_30cm":7.5,"C_45cm":10.5,"C_60cm":10.0},
    {"date":"2026-04-04","time":"18:00","N_15cm":5.5,"N_30cm":5.5,"M_15cm":6.0,"M_30cm":7.0,"M_45cm":7.0,"C_15cm":7.5,"C_20cm":6.0,"C_30cm":7.5,"C_45cm":10.5,"C_60cm":10.0},
    {"date":"2026-04-05","time":"18:40","N_15cm":6.0,"N_30cm":5.5,"M_15cm":6.5,"M_30cm":7.0,"M_45cm":7.0,"C_15cm":8.5,"C_20cm":7.0,"C_30cm":8.0,"C_45cm":11.0,"C_60cm":10.0},
    {"date":"2026-04-06","time":"11:00","N_15cm":6.0,"N_30cm":6.0,"M_15cm":6.5,"M_30cm":7.5,"M_45cm":6.0,"C_15cm":9.5,"C_20cm":8.0,"C_30cm":8.5,"C_45cm":10.5,"C_60cm":10.0},
    {"date":"2026-04-07","time":"18:00","N_15cm":6.5,"N_30cm":6.5,"M_15cm":8.0,"M_30cm":8.0,"M_45cm":7.5,"C_15cm":10.0,"C_20cm":8.0,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":10.5},
    {"date":"2026-04-08","time":"11:00","N_15cm":7.0,"N_30cm":6.5,"M_15cm":8.5,"M_30cm":8.5,"M_45cm":6.5,"C_15cm":10.5,"C_20cm":9.0,"C_30cm":9.5,"C_45cm":11.5,"C_60cm":10.5},
    {"date":"2026-04-08","time":"13:15","N_15cm":7.0,"N_30cm":6.5,"M_15cm":8.0,"M_30cm":8.5,"M_45cm":6.5,"C_15cm":10.0,"C_20cm":8.0,"C_30cm":9.5,"C_45cm":11.5,"C_60cm":11.0},
    {"date":"2026-04-08","time":"16:30","N_15cm":7.0,"N_30cm":6.5,"M_15cm":8.0,"M_30cm":8.5,"M_45cm":7.5,"C_15cm":9.5,"C_20cm":8.0,"C_30cm":9.5,"C_45cm":11.5,"C_60cm":10.5},
    {"date":"2026-04-08","time":"20:40","N_15cm":6.5,"N_30cm":6.5,"M_15cm":6.5,"M_30cm":8.0,"M_45cm":8.0,"C_15cm":7.0,"C_20cm":5.0,"C_30cm":9.0,"C_45cm":12.0,"C_60cm":11.0},
    {"date":"2026-04-09","time":"12:00","N_15cm":6.0,"N_30cm":6.0,"M_15cm":6.0,"M_30cm":7.5,"M_45cm":7.0,"C_15cm":7.5,"C_20cm":6.5,"C_30cm":8.5,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-11","time":"08:00","N_15cm":6.5,"N_30cm":6.0,"M_15cm":7.0,"M_30cm":8.0,"M_45cm":7.0,"C_15cm":9.5,"C_20cm":8.0,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":10.5},
    {"date":"2026-04-12","time":"12:00","N_15cm":6.5,"N_30cm":6.5,"M_15cm":8.0,"M_30cm":8.0,"M_45cm":7.5,"C_15cm":8.5,"C_20cm":7.5,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":11.0},
    {"date":"2026-04-13","time":"06:00","N_15cm":6.5,"N_30cm":6.0,"M_15cm":6.0,"M_30cm":8.0,"M_45cm":8.0,"C_15cm":6.0,"C_20cm":5.5,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":10.5},
    {"date":"2026-04-13","time":"15:30","N_15cm":6.0,"N_30cm":6.0,"M_15cm":6.0,"M_30cm":7.5,"M_45cm":7.5,"C_15cm":7.0,"C_20cm":6.0,"C_30cm":8.5,"C_45cm":11.0,"C_60cm":11.0},
    {"date":"2026-04-14","time":"06:00","N_15cm":6.5,"N_30cm":6.0,"M_15cm":7.0,"M_30cm":7.5,"M_45cm":7.5,"C_15cm":7.5,"C_20cm":6.5,"C_30cm":8.0,"C_45cm":11.0,"C_60cm":11.0},
    {"date":"2026-04-15","time":"06:00","N_15cm":6.5,"N_30cm":6.0,"M_15cm":7.0,"M_30cm":6.0,"M_45cm":7.5,"C_15cm":9.0,"C_20cm":7.5,"C_30cm":8.5,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-16","time":"06:00","N_15cm":7.0,"N_30cm":6.5,"M_15cm":8.0,"M_30cm":8.5,"M_45cm":7.5,"C_15cm":8.5,"C_20cm":8.0,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":10.5},
    {"date":"2026-04-16","time":"15:00","N_15cm":7.0,"N_30cm":6.5,"M_15cm":8.0,"M_30cm":9.0,"M_45cm":7.0,"C_15cm":9.0,"C_20cm":8.0,"C_30cm":9.0,"C_45cm":11.0,"C_60cm":10.5},
    {"date":"2026-04-16","time":"16:00","N_15cm":7.0,"N_30cm":7.0,"M_15cm":8.0,"M_30cm":9.0,"M_45cm":8.0,"C_15cm":7.5,"C_20cm":7.0,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":11.0},
    {"date":"2026-04-16","time":"20:00","N_15cm":6.5,"N_30cm":6.0,"M_15cm":6.0,"M_30cm":8.0,"M_45cm":8.0,"C_15cm":7.0,"C_20cm":6.0,"C_30cm":9.0,"C_45cm":11.5,"C_60cm":11.0},
    {"date":"2026-04-17","time":"15:00","N_15cm":6.0,"N_30cm":6.0,"M_15cm":6.5,"M_30cm":8.0,"M_45cm":7.5,"C_15cm":8.0,"C_20cm":7.0,"C_30cm":8.5,"C_45cm":11.5,"C_60cm":11.0}
  ],
  watering: [
    {"date":"2026-04-03","time":"12:15","event":"Regular watering","volume":400,"notes":""},
    {"date":"2026-04-03","time":"15:15","event":"Regular watering","volume":400,"notes":""},
    {"date":"2026-04-08","time":"18:00","event":"Stacked-pulse irrigation test","volume":400,"notes":"2 min ON / 20 min OFF x3"},
    {"date":"2026-04-12","time":"20:00","event":"Continued-pulse irrigation test","volume":400,"notes":"Single 6 min continuous run"},
    {"date":"2026-04-16","time":"15:00","event":"Regular watering","volume":400,"notes":""}
  ]
};

// ── SENSORS CONFIG ───────────────────────────────────────────────────────────
const SENSORS = {
  north:  [{key:'N_15cm',label:'N',depth:'15 cm'},{key:'N_30cm',label:'N',depth:'30 cm'}],
  middle: [{key:'M_15cm',label:'M',depth:'15 cm'},{key:'M_30cm',label:'M',depth:'30 cm'},{key:'M_45cm',label:'M',depth:'45 cm'}],
  crown:  [{key:'C_15cm',label:'C',depth:'15 cm'},{key:'C_20cm',label:'C',depth:'20 cm'},{key:'C_30cm',label:'C',depth:'30 cm'},{key:'C_45cm',label:'C',depth:'45 cm'},{key:'C_60cm',label:'C',depth:'60 cm'}]
};
const ALL_KEYS = ['N_15cm','N_30cm','M_15cm','M_30cm','M_45cm','C_15cm','C_20cm','C_30cm','C_45cm','C_60cm'];

let readings = {}, wateringEvents = [];

// ── HELPERS ──────────────────────────────────────────────────────────────────
function pad(n){return String(n).padStart(2,'0')}
function nowDate(){const d=new Date();return d.getFullYear()+'-'+pad(d.getMonth()+1)+'-'+pad(d.getDate())}
function nowTime(){const d=new Date();return pad(d.getHours())+':'+pad(d.getMinutes())}

function setProgress(step){
  for(let i=0;i<5;i++){
    const el=document.getElementById('prog-'+i);
    el.className='prog-seg'+(i<step?' done':i===step?' active':'');
  }
}

function goTo(pageId,step){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById(pageId).classList.add('active');
  if(step!==undefined)setProgress(step);
  if(pageId==='page-summary')buildSummary();
  window.scrollTo(0,0);
}

function showTab(tab){
  document.getElementById('tab-log').style.display = tab==='log'?'block':'none';
  document.getElementById('tab-data').style.display = tab==='data'?'block':'none';
  document.querySelectorAll('.tab').forEach((t,i)=>{
    t.classList.toggle('active',(tab==='log'&&i===0)||(tab==='data'&&i===1));
  });
  if(tab==='data') renderDataTable();
}

// ── LAST READING ─────────────────────────────────────────────────────────────
function getLastReading(){
  if(TENSIO_DATA.readings.length===0) return {};
  return TENSIO_DATA.readings[TENSIO_DATA.readings.length-1];
}

// ── SENSOR BUILDING ──────────────────────────────────────────────────────────
function buildSensorHTML(cid, list){
  const last = getLastReading();
  const el = document.getElementById(cid);
  el.innerHTML='';
  list.forEach(s=>{
    const val = last[s.key]!==undefined ? last[s.key] : 8.0;
    readings[s.key]=val;
    el.innerHTML+=`
      <div class="sensor-card">
        <div class="sensor-info">
          <div class="sensor-name">${s.label} <span style="color:var(--muted);font-weight:400">${s.depth}</span></div>
          <div class="sensor-depth">centibars</div>
        </div>
        <div class="stepper">
          <button class="step-btn" ontouchstart="" onclick="step('${s.key}',-0.5)">−</button>
          <div class="step-display" id="disp-${s.key}">${val.toFixed(1)}</div>
          <button class="step-btn" ontouchstart="" onclick="step('${s.key}',+0.5)">+</button>
        </div>
      </div>`;
  });
}

function step(key,delta){
  let v=Math.round((readings[key]+delta)*10)/10;
  if(v<0)v=0;
  readings[key]=v;
  document.getElementById('disp-'+key).textContent=v.toFixed(1);
}

function goToNorth(){
  const d=document.getElementById('inp-date').value;
  const t=document.getElementById('inp-time').value;
  if(!d||!t){alert('Please confirm date and time');return}
  buildSensorHTML('sensors-north',SENSORS.north);
  buildSensorHTML('sensors-middle',SENSORS.middle);
  buildSensorHTML('sensors-crown',SENSORS.crown);
  goTo('page-north',1);
}

// ── WATERING ─────────────────────────────────────────────────────────────────
function addWatering(){
  const d=document.getElementById('w-date').value;
  const t=document.getElementById('w-time').value;
  const v=parseFloat(document.getElementById('w-vol').value);
  if(!d||!t||isNaN(v)){alert('Please fill in all fields');return}
  wateringEvents.push({date:d,time:t,volume:v});
  const b=document.getElementById('watering-added-banner');
  b.style.display='block';
  b.innerHTML=`<div class="watering-added-info">${wateringEvents.length} event(s) added. Add another or go to summary.</div>`;
  document.getElementById('w-time').value=nowTime();
  window.scrollTo(0,0);
}

// ── SUMMARY ──────────────────────────────────────────────────────────────────
function buildSummary(){
  const d=document.getElementById('inp-date').value;
  const t=document.getElementById('inp-time').value;
  let html=`<div class="summary-group"><div class="summary-group-title">Tensiometer · ${d} ${t}</div>`;
  [...SENSORS.north,...SENSORS.middle,...SENSORS.crown].forEach(s=>{
    html+=`<div class="summary-row"><span class="summary-key">${s.label} ${s.depth}</span><span class="summary-val">${readings[s.key]?.toFixed(1)} cb</span></div>`;
  });
  html+='</div>';
  if(wateringEvents.length>0){
    html+='<div class="summary-group"><div class="summary-group-title">Watering events</div>';
    wateringEvents.forEach((w,i)=>{
      html+=`<div class="summary-row"><span class="summary-key">Event ${i+1} · ${w.time}</span><span class="summary-val">${w.volume} L</span></div>`;
    });
    html+='</div>';
  }
  document.getElementById('summary-content').innerHTML=html;
}

// ── DATA TABLE ───────────────────────────────────────────────────────────────
function renderDataTable(){
  const last10=[...TENSIO_DATA.readings].slice(-10).reverse();
  document.getElementById('data-count').textContent=`${TENSIO_DATA.readings.length} total readings · showing last 10`;
  let html=`<div style="overflow-x:auto;margin-bottom:16px"><table class="data-table">
    <tr><th>Date</th><th>Time</th><th>N15</th><th>N30</th><th>M15</th><th>M30</th><th>M45</th><th>C15</th><th>C20</th><th>C30</th><th>C45</th><th>C60</th></tr>`;
  last10.forEach(r=>{
    html+=`<tr><td>${r.date.substring(5)}</td><td>${r.time}</td>`;
    ALL_KEYS.forEach(k=>html+=`<td>${r[k]?.toFixed(1)}</td>`);
    html+='</tr>';
  });
  html+='</table></div>';
  document.getElementById('data-table-container').innerHTML=html;
}

// ── GITHUB SAVE ──────────────────────────────────────────────────────────────
async function submitAll(){
  goTo('page-submitting',4);
  const d=document.getElementById('inp-date').value;
  const t=document.getElementById('inp-time').value;

  // Add new reading to data
  const newReading = {date:d, time:t, ...readings};
  TENSIO_DATA.readings.push(newReading);

  // Add watering events
  wateringEvents.forEach(w=>{
    TENSIO_DATA.watering.push({date:w.date,time:w.time,event:'Regular watering',volume:w.volume,notes:''});
  });

  document.getElementById('submit-status').textContent='Getting current file from GitHub...';

  try {
    // Get current file SHA (needed for update)
    const getRes = await fetch(API_BASE, {
      headers: {
        'Authorization': `token ${GITHUB_TOKEN}`,
        'Accept': 'application/vnd.github.v3+json'
      }
    });
    const getJson = await getRes.json();
    const sha = getJson.sha;

    document.getElementById('submit-status').textContent='Saving to GitHub...';

    // Build updated HTML with new data embedded
    const newHtml = buildUpdatedHtml();
    const encoded = btoa(unescape(encodeURIComponent(newHtml)));

    const putRes = await fetch(API_BASE, {
      method: 'PUT',
      headers: {
        'Authorization': `token ${GITHUB_TOKEN}`,
        'Accept': 'application/vnd.github.v3+json',
        'Content-Type': 'application/json'
      },
      body: JSON.stringify({
        message: `Reading ${d} ${t}`,
        content: encoded,
        sha: sha
      })
    });

    if(!putRes.ok){
      const err=await putRes.json();
      throw new Error(err.message||'GitHub error');
    }

    const wc=wateringEvents.length;
    document.getElementById('done-msg').textContent=
      `Reading saved for ${d} at ${t}.`+(wc>0?`\n${wc} watering event${wc>1?'s':''} also saved.`:'');
    goTo('page-done',4);

  } catch(e) {
    // Still saved in memory even if GitHub failed
    document.getElementById('submit-status').innerHTML='';
    const errDiv=document.createElement('div');
    errDiv.className='error-card';
    errDiv.textContent='GitHub save failed: '+e.message+'\n\nData is saved locally — try again or download the file.';
    document.getElementById('page-submitting').querySelector('.loading-card').appendChild(errDiv);
    const retryBtn=document.createElement('button');
    retryBtn.className='btn btn-primary';
    retryBtn.style.marginTop='16px';
    retryBtn.textContent='Retry';
    retryBtn.onclick=submitAll;
    document.getElementById('page-submitting').querySelector('.loading-card').appendChild(retryBtn);
    const backBtn=document.createElement('button');
    backBtn.className='btn btn-secondary';
    backBtn.style.marginTop='8px';
    backBtn.textContent='Back to app';
    backBtn.onclick=()=>goTo('page-done',4);
    document.getElementById('page-submitting').querySelector('.loading-card').appendChild(backBtn);
  }
}

// ── BUILD UPDATED HTML ───────────────────────────────────────────────────────
function buildUpdatedHtml(){
  const src = document.documentElement.outerHTML;
  const newDataBlock = `var TENSIO_DATA = ${JSON.stringify(TENSIO_DATA, null, 2)};`;
  return src.replace(/var TENSIO_DATA = \{[\s\S]*?\};/, newDataBlock);
}

// ── RESET ────────────────────────────────────────────────────────────────────
function resetApp(){
  wateringEvents=[];
  readings={};
  document.getElementById('inp-date').value=nowDate();
  document.getElementById('inp-time').value=nowTime();
  document.getElementById('w-date').value=nowDate();
  document.getElementById('w-time').value=nowTime();
  document.getElementById('watering-added-banner').style.display='none';
  // Clear any error cards from submitting page
  const lc=document.getElementById('page-submitting').querySelector('.loading-card');
  lc.innerHTML='<div class="spinner"></div><div class="loading-text" id="submit-status">Saving...</div>';
  goTo('page-dt',0);
}

// ── DOWNLOAD ─────────────────────────────────────────────────────────────────
function setupDownload(){
  const html=buildUpdatedHtml();
  const blob=new Blob([html],{type:'text/html'});
  const url=URL.createObjectURL(blob);
  document.getElementById('download-link').href=url;
}

// ── INIT ─────────────────────────────────────────────────────────────────────
function init(){
  document.getElementById('inp-date').value=nowDate();
  document.getElementById('inp-time').value=nowTime();
  document.getElementById('w-date').value=nowDate();
  document.getElementById('w-time').value=nowTime();
  const last=getLastReading();
  const lastDate=last.date||'no readings yet';
  document.getElementById('header-sub').textContent=`Last reading: ${lastDate} · ${TENSIO_DATA.readings.length} total`;
  setupDownload();
}

init();
</script>
</body>
</html>
