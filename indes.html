
<!DOCTYPE html>
<html lang="cs">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Vstupní, výstupní, nebo obojí?</title>
<style>
:root {
  --ink: #172554;
  --blue: #2563eb;
  --orange: #ea580c;
  --purple: #7c3aed;
  --green: #15803d;
  --red: #b91c1c;
}
* { box-sizing: border-box; }
body {
  margin: 0;
  font-family: "Trebuchet MS", Arial, sans-serif;
  color: var(--ink);
  background:
    radial-gradient(circle at 10% 5%, #dbeafe, transparent 25rem),
    radial-gradient(circle at 95% 10%, #fce7f3, transparent 24rem),
    linear-gradient(135deg, #f8fafc, #eef2ff);
  min-height: 100vh;
}
.wrap {
  max-width: 1180px;
  margin: auto;
  padding: 24px 18px 40px;
}
header {
  text-align: center;
  padding: 28px 18px 24px;
  margin-bottom: 22px;
  border-radius: 26px;
  color: white;
  background: linear-gradient(120deg, #1d4ed8, #6d28d9, #c026d3);
  box-shadow: 0 12px 30px #4338ca30;
}
h1 {
  margin: 0 0 8px;
  font-size: clamp(1.8rem, 4vw, 2.7rem);
}
header p { margin: 0; color: #f5f3ff; }
.instructions {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  justify-content: center;
  margin-bottom: 20px;
}
.tip {
  background: white;
  border: 1px solid #dbeafe;
  border-radius: 14px;
  padding: 10px 14px;
  color: #334155;
}
.tip strong { color: #4f46e5; }
.cards-panel {
  background: white;
  border: 1px solid #dbeafe;
  border-radius: 22px;
  padding: 18px;
  box-shadow: 0 8px 24px #3341550c;
  margin-bottom: 22px;
}
.section-heading {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 0 0 14px;
}
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 10px;
  min-height: 72px;
}
.device {
  border: 2px solid #bfdbfe;
  background: linear-gradient(145deg, #eff6ff, white);
  color: #1e3a8a;
  border-radius: 15px;
  padding: 13px 10px;
  min-height: 80px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 6px;
  text-align: center;
  font-weight: 700;
  cursor: grab;
  user-select: none;
  box-shadow: 0 3px 0 #bfdbfe;
  transition: transform .15s, box-shadow .15s;
}
.device:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 0 #bfdbfe;
  border-color: #60a5fa;
}
.device .icon { font-size: 1.9rem; }
.device.selected {
  outline: 4px solid #fbbf24;
  outline-offset: 2px;
}
.device.correct {
  background: #dcfce7;
  border-color: #22c55e;
  color: #166534;
  box-shadow: 0 3px 0 #86efac;
}
.device.incorrect {
  background: #fee2e2;
  border-color: #ef4444;
  color: #991b1b;
  box-shadow: 0 3px 0 #fca5a5;
}
.zones {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 15px;
}
.zone {
  min-height: 225px;
  padding: 15px;
  border-radius: 20px;
  border: 2px dashed;
  transition: background .15s;
}
.zone h2 { margin: 0 0 5px; font-size: 1.15rem; }
.zone .hint { margin: 0 0 13px; font-size: .9rem; }
.zone .cards {
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
}
.zone.input {
  background: linear-gradient(150deg, #eff6ff, #dbeafe);
  border-color: #60a5fa;
}
.zone.input h2 { color: #1d4ed8; }
.zone.input .hint { color: #1e40af; }
.zone.output {
  background: linear-gradient(150deg, #fff7ed, #ffedd5);
  border-color: #fb923c;
}
.zone.output h2 { color: #c2410c; }
.zone.output .hint { color: #9a3412; }
.zone.both {
  background: linear-gradient(150deg, #f5f3ff, #ede9fe);
  border-color: #a78bfa;
}
.zone.both h2 { color: #6d28d9; }
.zone.both .hint { color: #5b21b6; }
.zone.over { border-style: solid; }
.zone.input.over { background: #bfdbfe; }
.zone.output.over { background: #fed7aa; }
.zone.both.over { background: #ddd6fe; }
.controls {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 12px;
  margin: 22px 0 14px;
}
button {
  border: 0;
  border-radius: 14px;
  padding: 13px 22px;
  font: inherit;
  font-weight: 800;
  cursor: pointer;
  box-shadow: 0 4px 0 #0f172a20;
}
.check {
  color: white;
  background: linear-gradient(120deg, #16a34a, #059669);
}
.reset { color: #334155; background: #e2e8f0; }
.status {
  text-align: center;
  font-weight: 800;
  font-size: 1.15rem;
  padding: 14px 16px;
  border-radius: 16px;
  background: white;
  border: 1px solid #e2e8f0;
}
.status.success {
  color: #166534;
  background: #dcfce7;
  border-color: #86efac;
}
.status.partial {
  color: #92400e;
  background: #fef3c7;
  border-color: #fcd34d;
}
.foot {
  text-align: center;
  color: #64748b;
  font-size: .85rem;
  margin-top: 20px;
}
@media (max-width: 760px) {
  .zones { grid-template-columns: 1fr; }
  .zone { min-height: 150px; }
  .zone .cards {
    grid-template-columns: repeat(auto-fit, minmax(125px, 1fr));
  }
}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <h1>Vstupní, výstupní, nebo obojí?</h1>
    <p>Roztřiď zařízení podle toho, jak počítač používají.</p>
  </header>

  <div class="instructions">
    <div class="tip">🖱️ <strong>Přetáhni</strong> kartu do správné skupiny.</div>
    <div class="tip">📱 Na dotykové obrazovce klepni na kartu a pak na skupinu.</div>
    <div class="tip">✅ Nakonec stiskni <strong>Zkontrolovat</strong>.</div>
  </div>

  <section class="cards-panel">
    <h2 class="section-heading">🧩 Kartičky k roztřídění</h2>
    <div class="cards" id="bank" data-zone="bank"></div>
  </section>

  <section class="zones">
    <div class="zone input" data-zone="input">
      <h2>⬇️ VSTUPNÍ ZAŘÍZENÍ</h2>
      <p class="hint">Posílají data nebo pokyny do počítače.</p>
      <div class="cards"></div>
    </div>
    <div class="zone output" data-zone="output">
      <h2>⬆️ VÝSTUPNÍ ZAŘÍZENÍ</h2>
      <p class="hint">Předávají informace z počítače uživateli.</p>
      <div class="cards"></div>
    </div>
    <div class="zone both" data-zone="both">
      <h2>↕️ OBOJÍ</h2>
      <p class="hint">Dokážou data přijímat i předávat.</p>
      <div class="cards"></div>
    </div>
  </section>

  <div class="controls">
    <button class="check" id="check">✓ Zkontrolovat</button>
    <button class="reset" id="reset">↻ Začít znovu</button>
  </div>
  <div class="status" id="status" role="status" aria-live="polite">
    Připraveno? Roztřiď všech 14 kartiček.
  </div>
  <div class="foot">Aktivita neukládá žádné údaje a funguje i offline.</div>
</div>

<script>
const devices = [
  {name:"Klávesnice", icon:"⌨️", answer:"input"},
  {name:"Myš", icon:"🖱️", answer:"input"},
  {name:"Mikrofon", icon:"🎙️", answer:"input"},
  {name:"Webkamera", icon:"📷", answer:"input"},
  {name:"Skener", icon:"📠", answer:"input"},
  {name:"Čtečka čárových kódů", icon:"▥", answer:"input"},
  {name:"Monitor", icon:"🖥️", answer:"output"},
  {name:"Reproduktory", icon:"🔊", answer:"output"},
  {name:"Sluchátka bez mikrofonu", icon:"🎧", answer:"output"},
  {name:"Tiskárna", icon:"🖨️", answer:"output"},
  {name:"Projektor", icon:"📽️", answer:"output"},
  {name:"Dotykový displej", icon:"👆", answer:"both"},
  {name:"Sluchátka s mikrofonem", icon:"🎧", answer:"both"},
  {name:"Multifunkční tiskárna se skenerem", icon:"🖨️", answer:"both"}
];

const bank = document.getElementById("bank");
const statusBox = document.getElementById("status");
let selected = null;

function makeCard(d) {
  const el = document.createElement("div");
  el.className = "device";
  el.draggable = true;
  el.tabIndex = 0;
  el.setAttribute("role", "button");
  el.setAttribute("aria-label", d.name + ", vyber nebo přetáhni");
  el.dataset.name = d.name;
  el.dataset.answer = d.answer;
  el.innerHTML = `<span class="icon" aria-hidden="true">${d.icon}</span><span>${d.name}</span>`;

  el.addEventListener("dragstart", e => {
    selected = el;
    e.dataTransfer.setData("text/plain", d.name);
    e.dataTransfer.effectAllowed = "move";
  });

  el.addEventListener("click", () => {
    if (selected === el) {
      el.classList.remove("selected");
      selected = null;
      return;
    }
    if (selected) selected.classList.remove("selected");
    selected = el;
    el.classList.add("selected");
    statusBox.textContent = "Vybráno: " + d.name + ". Klepni na cílovou skupinu.";
    statusBox.className = "status";
  });

  el.addEventListener("keydown", e => {
    if (e.key === "Enter" || e.key === " ") {
      e.preventDefault();
      el.click();
    }
  });
  return el;
}

function moveCard(card, zone) {
  const target = zone.querySelector(".cards") || zone;
  target.appendChild(card);
  card.classList.remove("selected", "correct", "incorrect");
  selected = null;
  statusBox.className = "status";
  statusBox.textContent = "Pokračuj v třídění. Až budeš hotov/a, klikni na Zkontrolovat.";
}

function setupZones() {
  document.querySelectorAll(".zone").forEach(zone => {
    zone.addEventListener("dragover", e => {
      e.preventDefault();
      zone.classList.add("over");
    });
    zone.addEventListener("dragleave", () => zone.classList.remove("over"));
    zone.addEventListener("drop", e => {
      e.preventDefault();
      zone.classList.remove("over");
      if (selected) moveCard(selected, zone);
    });
    zone.addEventListener("click", e => {
      if (selected && !e.target.closest(".device")) moveCard(selected, zone);
    });
  });
}

function checkAnswers() {
  const cards = [...document.querySelectorAll(".device")];
  let correct = 0;

  cards.forEach(card => {
    const zone = card.closest("[data-zone]");
    const actual = zone ? zone.dataset.zone : "bank";
    const ok = actual === card.dataset.answer;
    card.classList.remove("selected", "correct", "incorrect");
    card.classList.add(ok ? "correct" : "incorrect");
    if (ok) correct++;
  });

  selected = null;
  if (correct === devices.length) {
    statusBox.className = "status success";
    statusBox.textContent = `Výborně! ${correct} z ${devices.length} správně.`;
  } else {
    statusBox.className = "status partial";
    statusBox.textContent = `${correct} z ${devices.length} správně. Zelené karty jsou správně, červené zkus přesunout.`;
  }
}

function resetAll() {
  document.querySelectorAll(".device").forEach(c => c.remove());
  document.querySelectorAll(".zone .cards").forEach(c => c.innerHTML = "");
  selected = null;
  devices.slice().sort(() => Math.random() - 0.5).forEach(d => bank.appendChild(makeCard(d)));
  statusBox.className = "status";
  statusBox.textContent = "Připraveno? Roztřiď všech 14 kartiček.";
}

devices.slice().sort(() => Math.random() - 0.5).forEach(d => bank.appendChild(makeCard(d)));
setupZones();
document.getElementById("check").addEventListener("click", checkAnswers);
document.getElementById("reset").addEventListener("click", resetAll);
</script>
</body>
</html>
'''
path = Path("/mnt/data/trideni_zarizeni_barevne_vylepsene.html")
path.write_text(html, encoding="utf-8")
print(f"Vytvořen barevně upravený soubor: {path}")
print("Barvy: modrá = vstup, oranžová = výstup, fialová = obojí, zelená/červená = kontrola odpovědí.")
