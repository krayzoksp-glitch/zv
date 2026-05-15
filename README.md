<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maladies du sang — Fiche de révision complète</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:#f8f7f4;color:#1a1a1a;line-height:1.6}
.page{max-width:860px;margin:0 auto;padding:2rem 1.5rem}
.header{padding:1.5rem 0 1rem;border-bottom:1px solid #e0ded8;margin-bottom:1.5rem}
.header h1{font-size:24px;font-weight:600;color:#1a1a1a}
.header p{font-size:14px;color:#6b6b6b;margin-top:4px}
.nav{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:1.5rem}
.nav-btn{font-size:13px;padding:7px 16px;border-radius:8px;border:1px solid #d0cec8;background:#fff;color:#6b6b6b;cursor:pointer;transition:all 0.15s;font-family:inherit}
.nav-btn:hover{background:#f0eeea}
.nav-btn.active{background:#CECBF6;border-color:#7F77DD;color:#3C3489;font-weight:600}
.section{display:none}
.section.visible{display:block}
.grid2{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:12px;margin-bottom:1rem}
.grid3{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:12px;margin-bottom:1rem}
.card{background:#fff;border:1px solid #e0ded8;border-radius:12px;padding:1rem 1.25rem}
.card-title{font-size:14px;font-weight:600;color:#1a1a1a;margin-bottom:8px}
.card ul{padding-left:16px}
.card li{font-size:13px;color:#4a4a4a;line-height:1.8}
.card li b{color:#1a1a1a;font-weight:600}
.badge{display:inline-block;font-size:11px;font-weight:600;padding:2px 9px;border-radius:20px;margin-right:4px;margin-bottom:4px}
.badge-purple{background:#EEEDFE;color:#3C3489}
.badge-teal{background:#E1F5EE;color:#085041}
.badge-coral{background:#FAECE7;color:#712B13}
.badge-blue{background:#E6F1FB;color:#0C447C}
.badge-amber{background:#FAEEDA;color:#633806}
.badge-red{background:#FCEBEB;color:#791F1F}
.badge-green{background:#EAF3DE;color:#27500A}
.badge-gray{background:#F1EFE8;color:#444441}
.badge-pink{background:#FBEAF0;color:#72243E}
.highlight{background:#f0eeea;border-left:3px solid #7F77DD;border-radius:0 8px 8px 0;padding:0.75rem 1rem;margin-bottom:1rem;font-size:13px;color:#4a4a4a;line-height:1.7}
.highlight b{color:#1a1a1a;font-weight:600}
.alert{background:#FAEEDA;border-radius:8px;padding:0.75rem 1rem;margin-bottom:1rem;font-size:13px;color:#633806;line-height:1.7}
.alert b{color:#412402;font-weight:600}
.danger{background:#FCEBEB;border-radius:8px;padding:0.75rem 1rem;margin-bottom:1rem;font-size:13px;color:#791F1F;line-height:1.7}
.danger b{color:#501313;font-weight:600}
.success{background:#EAF3DE;border-radius:8px;padding:0.75rem 1rem;margin-bottom:1rem;font-size:13px;color:#27500A;line-height:1.7}
.success b{color:#173404;font-weight:600}
.table-wrap{overflow-x:auto;margin-bottom:1rem}
table{width:100%;border-collapse:collapse;font-size:13px}
th{background:#f0eeea;color:#4a4a4a;font-weight:600;padding:9px 12px;text-align:left;border-bottom:1px solid #e0ded8}
td{padding:9px 12px;border-bottom:1px solid #e0ded8;color:#4a4a4a;line-height:1.6}
td b{color:#1a1a1a;font-weight:600}
.row-ok td{color:#27500A}
.row-warn td{color:#633806}
.row-danger td{color:#791F1F}
.subtitle{font-size:16px;font-weight:600;color:#1a1a1a;margin:1.5rem 0 0.75rem;padding-bottom:6px;border-bottom:1px solid #e0ded8}
.tag-row{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:1rem}
.schema{background:#f0eeea;border-radius:12px;padding:1rem 1.25rem;margin-bottom:1rem}
.schema-row{display:flex;align-items:center;gap:8px;margin-bottom:8px;flex-wrap:wrap}
.schema-box{font-size:12px;font-weight:600;padding:5px 11px;border-radius:8px;border:1px solid}
.arrow{color:#6b6b6b;font-size:14px}
.step-row{display:flex;align-items:flex-start;gap:12px;margin-bottom:10px}
.step-num{min-width:24px;height:24px;border-radius:50%;background:#EEEDFE;color:#3C3489;font-size:12px;font-weight:600;display:flex;align-items:center;justify-content:center;flex-shrink:0;margin-top:2px}
.step-content{font-size:13px;color:#4a4a4a;line-height:1.7}
.step-content b{color:#1a1a1a;font-weight:600}
.quiz-card{background:#fff;border:1px solid #e0ded8;border-radius:12px;padding:1rem 1.25rem;margin-bottom:1rem}
.quiz-q{font-size:14px;font-weight:600;color:#1a1a1a;margin-bottom:10px}
.quiz-opts{display:flex;flex-direction:column;gap:6px}
.quiz-opt{font-size:13px;padding:9px 13px;border-radius:8px;border:1px solid #d0cec8;background:#fff;color:#4a4a4a;cursor:pointer;text-align:left;transition:all 0.15s;font-family:inherit}
.quiz-opt:hover{background:#f0eeea}
.quiz-opt.correct{background:#EAF3DE;border-color:#639922;color:#27500A}
.quiz-opt.wrong{background:#FCEBEB;border-color:#E24B4A;color:#791F1F}
.quiz-feedback{font-size:13px;margin-top:8px;padding:9px 13px;border-radius:8px;display:none;line-height:1.6}
.quiz-feedback.show{display:block}
.feedback-ok{background:#EAF3DE;color:#27500A}
.feedback-ko{background:#FCEBEB;color:#791F1F}
.reset-btn{font-size:12px;padding:5px 11px;border-radius:8px;border:1px solid #d0cec8;background:#f0eeea;color:#6b6b6b;cursor:pointer;margin-top:8px;display:none;font-family:inherit}
.reset-btn.show{display:inline-block}
.score-box{background:#f0eeea;border-radius:12px;padding:1rem 1.25rem;margin-bottom:1.5rem;display:flex;align-items:center;gap:16px}
.score-num{font-size:28px;font-weight:600;color:#1a1a1a}
.score-label{font-size:13px;color:#6b6b6b}
.reset-all-btn{margin-left:auto;font-size:12px;padding:7px 14px;border-radius:8px;border:1px solid #d0cec8;background:#fff;color:#4a4a4a;cursor:pointer;font-family:inherit}
.reset-all-btn:hover{background:#f0eeea}
.tree-node{background:#fff;border:1px solid #e0ded8;border-radius:8px;padding:5px 12px;font-size:12px;font-weight:600;display:inline-block}
</style>
</head>
<body>
<div class="page">

<div class="header">
  <h1>Maladies du sang — fiche de révision complète</h1>
  <p>EUSES Terres de l'Ebre · Fisiopatologia i Patologia General</p>
</div>

<div class="nav">
  <button class="nav-btn active" onclick="showSection('sang',this)">Sang &amp; hématopoïèse</button>
  <button class="nav-btn" onclick="showSection('anemies',this)">Anémies</button>
  <button class="nav-btn" onclick="showSection('polyglobulie',this)">Polyglobulie</button>
  <button class="nav-btn" onclick="showSection('leucocytes',this)">Leucocytes</button>
  <button class="nav-btn" onclick="showSection('plaquettes',this)">Plaquettes &amp; coagulation</button>
  <button class="nav-btn" onclick="showSection('diagnostic',this)">Arbre diagnostique</button>
  <button class="nav-btn" onclick="showSection('quiz',this)">Quiz (10 q.)</button>
</div>

<!-- SANG -->
<div id="sang" class="section visible">
  <div class="highlight"><b>Le sang</b> = fluide circulant dans le système cardiovasculaire. <b>55%</b> plasma + <b>45%</b> éléments figurés (95% hématies). Volume total ≈ 5 litres.</div>
  <div class="grid3">
    <div class="card">
      <div class="card-title">Hématies</div>
      <ul>
        <li>Disque biconcave, <b>durée de vie : 120 j</b></li>
        <li>Transport O₂ (hémoglobine) et CO₂ (anhydrase carbonique)</li>
        <li>H : <b>4,5–5,7 × 10⁶/µl</b> | F : 3,9–5 × 10⁶/µl</li>
        <li>Hb H : <b>13,5–17,5 g/dl</b> | F : 12–16 g/dl</li>
        <li>Hte H : 41–53% | F : 36–46%</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Leucocytes</div>
      <ul>
        <li>Défense contre pathogènes</li>
        <li>Total : <b>4 500–11 500/µl</b></li>
        <li>Neutrophiles <b>60%</b> (4 500/µl)</li>
        <li>Lymphocytes 34% (2 500/µl)</li>
        <li>Monocytes 4%, Éosinophiles &lt;3%, Basophiles 1%</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Plaquettes &amp; plasma</div>
      <ul>
        <li>Plaquettes : <b>150 000–450 000/µl</b></li>
        <li>Issues des mégacaryocytes</li>
        <li>Rôle : coagulation (hémostase)</li>
        <li>Plasma : 93% eau + 7% protéines (albumine +++)</li>
      </ul>
    </div>
  </div>

  <div class="subtitle">Hématopoïèse</div>
  <div class="highlight"><b>Définition :</b> formation des cellules sanguines dans la moelle osseuse rouge (chez l'adulte : vertèbres, sternum, crête iliaque). Capacité : 10 milliards d'hématies/heure + 100 millions de leucocytes/heure. Cellules souches pluripotentielles → deux lignées principales.</div>
  <div class="schema">
    <div class="schema-row">
      <div class="schema-box" style="background:#EEEDFE;border-color:#7F77DD;color:#3C3489;">Cellule souche pluripotentielle</div>
      <span class="arrow">→</span>
      <div class="schema-box" style="background:#E1F5EE;border-color:#1D9E75;color:#085041;">Lignée myéloïde</div>
      <span class="arrow">+</span>
      <div class="schema-box" style="background:#E6F1FB;border-color:#378ADD;color:#0C447C;">Lignée lymphoïde</div>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#E1F5EE;border-color:#1D9E75;color:#085041;">Myéloïde</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Hématies · Plaquettes · Neutrophiles · Éosinophiles · Basophiles · Monocytes/Macrophages</span>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#E6F1FB;border-color:#378ADD;color:#0C447C;">Lymphoïde</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Lymphocytes B → Plasmocytes · Lymphocytes T · Cellules NK</span>
    </div>
  </div>

  <div class="subtitle">Érythropoïèse en détail</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Régulation</div>
      <ul>
        <li><b>Activation :</b> EPO (érythropoïétine) + fer + vitamines (B12, folates)</li>
        <li><b>Inhibition :</b> IL-1 et TNF → augmentés dans les inflammations chroniques</li>
        <li>Érythropoïèse inefficace physiologique : 5–10% des érythroblastes détruits</li>
        <li><b>Hémocatérèse :</b> destruction physiologique des hématies après 90–120 j (rate)</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Étapes de maturation</div>
      <div class="step-row"><div class="step-num">1</div><div class="step-content"><b>Proérythroblaste</b> → synthèse ribosomes</div></div>
      <div class="step-row"><div class="step-num">2</div><div class="step-content"><b>Érythroblastes</b> → accumulation hémoglobine</div></div>
      <div class="step-row"><div class="step-num">3</div><div class="step-content"><b>Réticulocyte</b> → éjection du noyau (normal : 25 000–75 000/mm³)</div></div>
      <div class="step-row"><div class="step-num">4</div><div class="step-content"><b>Érythrocyte</b> mature → libéré dans la circulation</div></div>
    </div>
  </div>
  <div class="alert"><b>Réticulocytes :</b> indicateur clé de l'activité médullaire. Élevés → anémie régénérative (hémolyse, saignement). Bas → anémie arégénérative (production insuffisante).</div>
</div>

<!-- ANEMIES -->
<div id="anemies" class="section">
  <div class="highlight"><b>Définition :</b> Hb &lt; 13 g/dl (homme) / &lt; 12 g/dl (femme) / &lt; 11 g/dl (femme enceinte). La clinique dépend surtout de la <b>vitesse d'installation</b>.</div>

  <div class="subtitle">Classification par VCM</div>
  <div class="grid3">
    <div class="card">
      <div class="card-title"><span class="badge badge-coral">VCM &lt; 80 fl — microcytaire</span></div>
      <ul>
        <li><b>Anémie ferriprive</b> (la + fréquente au monde)</li>
        <li><b>Thalassémie</b> : défaut de synthèse des chaînes de globine (héréditaire). Fer normal ou élevé</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-teal">VCM 80–100 fl — normocytaire</span></div>
      <ul>
        <li>Saignement aigu</li>
        <li>Anémie des maladies chroniques</li>
        <li>Insuffisance rénale chronique</li>
        <li>Aplasie médullaire</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-purple">VCM &gt; 100 fl — macrocytaire</span></div>
      <ul>
        <li>Déficit B12 ou folates</li>
        <li>Alcoolisme, hépatopathie</li>
        <li>Réticulocytose (hémolyse)</li>
      </ul>
    </div>
  </div>

  <div class="subtitle">Anémie ferriprive — la plus fréquente (15% population mondiale)</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Causes</div>
      <ul>
        <li><b>↑ besoins :</b> grossesse, croissance rapide (enfant, adolescent)</li>
        <li><b>↑ pertes :</b> saignements chroniques digestifs/urinaires, hyperménorrhée, dons fréquents de sang</li>
        <li><b>↓ apport :</b> régime végétarien strict, malnutrition</li>
        <li><b>↓ absorption :</b> maladie cœliaque, chirurgie gastrique/bariatrique</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Stades évolutifs</div>
      <div class="step-row"><div class="step-num">1</div><div class="step-content"><b>Déplétion des réserves :</b> ferritine ↓, pas d'anémie. Asthénie, faiblesse musculaire</div></div>
      <div class="step-row"><div class="step-num">2</div><div class="step-content"><b>↓ érythropoïèse :</b> anémie normocytaire. Transferrine ↑, IST ↓</div></div>
      <div class="step-row"><div class="step-num">3</div><div class="step-content"><b>Déficit marqué :</b> anémie <b>microcytaire hyporégénérative</b>. Ferritine très basse</div></div>
    </div>
  </div>
  <div class="alert"><b>Biologie :</b> Hb ↓, VCM &lt; 80 fl, réticulocytes ↓, fer ↓, transferrine ↑, <b>ferritine sérique basse</b> (meilleur marqueur des réserves en fer).</div>
  <div class="tag-row">
    <span class="badge badge-coral">Koïlonychie (ongles en cuillère)</span>
    <span class="badge badge-coral">Chéilite angulaire</span>
    <span class="badge badge-coral">Glossite</span>
    <span class="badge badge-coral">Fragilité unguéale et capillaire</span>
    <span class="badge badge-coral">Syndrome pica</span>
  </div>

  <div class="subtitle">Anémies mégaloblastiques (B12 / folates)</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Mécanisme &amp; biologie</div>
      <ul>
        <li>Altération de la synthèse d'ADN → hématies grandes (VCM &gt; 100 fl)</li>
        <li>Toutes les lignées touchées → <b>pancytopénie fréquente</b></li>
        <li>Érythropoïèse inefficace augmentée → hyperbilirubinémie (ictère)</li>
        <li><b>Anémie pernicieuse :</b> destruction des cellules pariétales gastriques → pas de facteur intrinsèque → déficit B12 (cause la + fréquente de déficit B12)</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Manifestations cliniques</div>
      <ul>
        <li>Installation lente</li>
        <li>Glossite, chéilite, atteintes cutanéo-muqueuses</li>
        <li><b>Signes neurologiques (B12 spécifiques) :</b></li>
        <li>Démyélinisation SN périphérique + moelle épinière</li>
        <li>Ataxie, troubles de la sensibilité</li>
        <li>Démence, troubles psychiatriques</li>
        <li><b>Le déficit en folates n'entraîne PAS de signes neurologiques</b></li>
      </ul>
    </div>
  </div>

  <div class="subtitle">Anémie des maladies chroniques — 2e cause la plus fréquente</div>
  <div class="schema">
    <div class="schema-row">
      <div class="schema-box" style="background:#FAEEDA;border-color:#EF9F27;color:#633806;">Inflammation chronique (TBC, néoplasie, maladies systémiques…)</div>
      <span class="arrow">→</span>
      <div class="schema-box" style="background:#FAECE7;border-color:#D85A30;color:#712B13;">Activation macrophages + lymphocytes T → IL-1 + TNF</div>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#FAECE7;border-color:#D85A30;color:#712B13;">Inhibition de l'érythropoïèse</div>
      <span class="arrow">→</span>
      <div class="schema-box" style="background:#FCEBEB;border-color:#E24B4A;color:#791F1F;">Anémie normocytaire hyporégénérative</div>
    </div>
  </div>
  <div class="success"><b>Traitement :</b> traiter la cause → guérison de l'anémie. Hb généralement &gt; 8 g/dl. Réticulocytes bas. Ferritine normale ou élevée (contrairement à la carence en fer où elle est basse).</div>

  <div class="subtitle">Anémies hémolytiques</div>
  <div class="highlight"><b>Hémolyse :</b> destruction prématurée des hématies. État compensé si moelle ↑ production ×6–8. Si durée de vie &lt; 15 j → anémie hémolytique.</div>
  <div class="grid3">
    <div class="card">
      <div class="card-title">Membrane</div>
      <ul><li>Sphérocytose héréditaire</li><li>Elliptocytose</li><li>HPN (hémoglobinurie paroxystique nocturne)</li><li>Acanthocytose</li></ul>
    </div>
    <div class="card">
      <div class="card-title">Intérieur de l'hématie</div>
      <ul><li>Déficit G6PD</li><li>Déficit pyruvate kinase</li><li>Hémoglobinopathies (drépanocytose)</li><li>Thalassémies</li></ul>
    </div>
    <div class="card">
      <div class="card-title">Facteurs extrinsèques</div>
      <ul><li>Hypersplénisme</li><li>Anémie hémolytique auto-immune</li><li>Prothèses cardiaques métalliques</li><li>Paludisme, babésiose</li></ul>
    </div>
  </div>
  <div class="alert"><b>Marqueurs biologiques :</b> ↑ réticulocytes (régénérative), ↑ LDH, ↑ bilirubine indirecte, ↓ haptoglobine. Hémolyse extravasculaire → splénomégalie. Hémolyse intravasculaire → hémoglobinurie.</div>

  <div class="subtitle">Clinique de l'anémie selon sévérité</div>
  <div class="table-wrap">
    <table>
      <tr><th>Hémoglobine</th><th>Signes cliniques</th></tr>
      <tr class="row-ok"><td><b>8–9 g/dl</b></td><td>Généralement bien tolérée. Asthénie, faiblesse, intolérance à l'effort. Mécanisme compensatoire : ↑ 2,3-DPG → ↑ extraction O₂ (de 25% à 60%)</td></tr>
      <tr class="row-warn"><td><b>&lt; 8 g/dl</b></td><td>↑ débit cardiaque compensateur</td></tr>
      <tr class="row-danger"><td><b>≈ 5 g/dl</b></td><td>Tachycardie au repos</td></tr>
      <tr class="row-danger"><td><b>Aiguë (quelle que soit la valeur)</b></td><td>Perte de volume → hypotension, vertiges, signes de bas débit cardiaque</td></tr>
    </table>
  </div>
  <div class="danger"><b>Signe caractéristique dans tous les cas :</b> pâleur cutanéo-muqueuse.</div>
</div>

<!-- POLYGLOBULIE -->
<div id="polyglobulie" class="section">
  <div class="highlight"><b>Polyglobulie = polycythémie = érythrocytose</b> : Hte &gt; 55% chez l'homme ou &gt; 50% chez la femme. Augmentation de la masse globulaire totale.</div>

  <div class="subtitle">Causes selon le taux d'EPO</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title"><span class="badge badge-amber">EPO élevée — polyglobulie secondaire</span></div>
      <ul>
        <li><b>Sécrétion inadéquate d'EPO :</b></li>
        <li>Néoplasies productrices d'EPO (cancer du rein, du foie)</li>
        <li><b>Sécrétion réactionnelle à l'hypoxémie :</b></li>
        <li>Insuffisance respiratoire chronique</li>
        <li>Altitude élevée (réponse adaptative normale)</li>
        <li>Intoxication CO (<b>tabagisme</b>)</li>
        <li>Cardiopathies congénitales cyanogènes</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-red">EPO basse — polyglobulie primaire</span></div>
      <ul>
        <li><b>Polycythémie vraie (Vaquez) :</b></li>
        <li>Maladie myéloproliférative clonale</li>
        <li>Production autonome d'hématies indépendante de l'EPO</li>
        <li>Mutation JAK2 dans &gt; 95% des cas</li>
        <li>Risque thrombotique majeur (AVC, IDM, TVP)</li>
      </ul>
    </div>
  </div>

  <div class="subtitle">Bilan diagnostique</div>
  <div class="schema">
    <div class="schema-row">
      <div class="schema-box" style="background:#EEEDFE;border-color:#7F77DD;color:#3C3489;">Hte &gt; 55% H / &gt; 50% F</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Gazométrie · Carboxyhémoglobine · Échocardiographie · Fonction pulmonaire</span>
      <span class="arrow">→</span>
      <div class="schema-box" style="background:#E1F5EE;border-color:#1D9E75;color:#085041;">Dosage EPO</div>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#FAEEDA;border-color:#EF9F27;color:#633806;">EPO ↑</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Cause secondaire (hypoxie ou tumeur sécrétante)</span>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#FCEBEB;border-color:#E24B4A;color:#791F1F;">EPO ↓ ou normale basse</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Polycythémie vraie → recherche mutation JAK2</span>
    </div>
  </div>

  <div class="subtitle">Clinique de la polyglobulie</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Signes cliniques</div>
      <ul>
        <li><b>Faciès érythrosique</b> (visage rouge violacé) caractéristique</li>
        <li>Céphalées, vertiges, acouphènes</li>
        <li>Prurit après douche chaude (polycythémie vraie)</li>
        <li>Troubles visuels</li>
        <li>Splénomégalie (polycythémie vraie)</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Complications</div>
      <ul>
        <li>Hyperviscosité sanguine → thromboses artérielles et veineuses</li>
        <li>AVC, IDM, thrombose porte</li>
        <li>Risque hémorragique paradoxal</li>
        <li>Évolution possible vers myélofibrose ou leucémie aiguë (polycythémie vraie)</li>
      </ul>
    </div>
  </div>
  <div class="alert"><b>À retenir :</b> la polyglobulie secondaire est une réponse adaptative à l'hypoxie (normale en altitude, pathologique si IRC ou tabac). La polycythémie vraie est une hémopathie maligne.</div>
</div>

<!-- LEUCOCYTES -->
<div id="leucocytes" class="section">
  <div class="highlight"><b>Leucocytes normaux :</b> 4 500–11 500/µl. Trastornos : <b>quantitatifs</b> (leucocytoses / leucocytopénies) ou <b>prolifératifs</b> (leucémies, lymphomes).</div>

  <div class="subtitle">Leucocytoses</div>
  <div class="grid3">
    <div class="card">
      <div class="card-title"><span class="badge badge-coral">Neutrophile — la + fréquente</span></div>
      <p style="font-size:12px;color:#4a4a4a;margin-bottom:6px;">Neutrophiles &gt; 7 500/µl</p>
      <ul>
        <li><b>Primaire :</b> tumeurs myéloprolifératives, conditions génétiques</li>
        <li><b>Secondaire :</b> infections, inflammation, corticoïdes, tabac, grossesse, asplénie, stress organique (IDM, exercice intense, coup de chaleur)</li>
        <li><b>Cayados</b> = neutrophiles immatures → déviation gauche (signe d'infection sévère)</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-blue">Lymphocytaire</span></div>
      <p style="font-size:12px;color:#4a4a4a;margin-bottom:6px;">Lymphocytes &gt; 4 800/µl</p>
      <ul>
        <li><b>Virales :</b> MNI (EBV), CMV, varicelle, grippe, rubéole, oreillons</li>
        <li>Bactériennes (occasionnel) : TB, syphilis, brucellose</li>
        <li>Hypersensibilité (médicaments)</li>
        <li>Stress (traumatisme grave, splénectomie)</li>
        <li>Processus lymphoprolifératifs (LLC…)</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-amber">Éosinophile</span></div>
      <p style="font-size:12px;color:#4a4a4a;margin-bottom:6px;">Éosinophiles &gt; 500/µl</p>
      <ul>
        <li>Parasitoses (helminthes, S. stercoralis)</li>
        <li>Allergies (rhinite, asthme)</li>
        <li>Tumeurs solides</li>
        <li>Syndromes prolifératifs (leucémies chroniques, lymphomes)</li>
        <li>Médicaments</li>
      </ul>
    </div>
  </div>

  <div class="subtitle">Leucocytopénies</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Neutropénie (&lt; 2 500/µl)</div>
      <ul>
        <li>Chimiothérapie (cause principale)</li>
        <li>Infections (destruction, séquestration)</li>
        <li>AINS, chloramphénicol, phénytoïne</li>
        <li>Atteinte médullaire (aplasie, SMD)</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Lymphocytopénie (&lt; 1 000/µl)</div>
      <ul>
        <li><b>VIH :</b> destruction des CD4+ (lymphocytes T auxiliaires)</li>
        <li>Corticoïdes</li>
        <li>Radiothérapie</li>
      </ul>
    </div>
  </div>

  <div class="subtitle">Risque infectieux selon neutrophiles</div>
  <div class="table-wrap">
    <table>
      <tr><th>Neutrophiles/µl</th><th>Risque</th><th>Prise en charge</th></tr>
      <tr class="row-ok"><td><b>&gt; 1 500</b></td><td>Aucun</td><td>Normal</td></tr>
      <tr class="row-ok"><td><b>1 000–1 500</b></td><td>Très faible</td><td>Surveillance</td></tr>
      <tr class="row-warn"><td><b>500–1 000</b></td><td>Modéré</td><td>Traitement ambulatoire possible si infection</td></tr>
      <tr class="row-danger"><td><b>&lt; 500</b></td><td>Élevé</td><td>Hospitalisation obligatoire si infection</td></tr>
      <tr class="row-danger"><td><b>&lt; 200</b></td><td>Très élevé</td><td>Hospitalisation obligatoire</td></tr>
    </table>
  </div>
  <div class="danger"><b>Sites infectieux les + fréquents en neutropénie :</b> cavité orale, muqueuses, peau, région péri-rectale → risque de bactériémie → sepsis.</div>

  <div class="subtitle">Leucémies &amp; lymphomes</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Leucémies</div>
      <ul>
        <li>Maladie tumorale maligne des précurseurs hématopoïétiques (clone médullaire)</li>
        <li><b>LAL</b> (aiguë lymphoïde) : + fréquente chez l'enfant (pic 4 ans)</li>
        <li><b>LAM</b> (aiguë myéloïde) : + fréquente chez l'adulte (pic 70 ans)</li>
        <li>Étiologie : chimio/radiothérapie préalables, expositions chimiques</li>
        <li>Clinique : pancytopénie, syndrome constitutionnel, blastes au frottis</li>
        <li>Diagnostic : immunophénotypage + cytogénétique sur moelle</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Lymphomes</div>
      <ul>
        <li>Prolifération néoplasique de lymphocytes (ganglions / rate)</li>
        <li><b>Hodgkin :</b> lymphocytes B, cellule de Reed-Sternberg. Pics 15–40 ans et &gt; 60 ans</li>
        <li><b>Non-Hodgkin :</b> B 80% / T 20%, 6× plus fréquent que LH</li>
        <li><b>Étiologie :</b> EBV, H. pylori, radiations, immunosuppresseurs</li>
        <li><b>Symptômes B</b> (fièvre, sueurs nocturnes, perte de poids &gt; 10%) → 25% des cas → mauvais pronostic</li>
        <li>Diagnostic : biopsie ganglionnaire obligatoire</li>
      </ul>
    </div>
  </div>
</div>

<!-- PLAQUETTES -->
<div id="plaquettes" class="section">
  <div class="highlight"><b>Plaquettes normales :</b> 150 000–450 000/µl. Issues des mégacaryocytes (stimulés par la thrombopoïétine, produite par le foie). Rôle central dans l'hémostase primaire.</div>

  <div class="subtitle">Troubles quantitatifs des plaquettes</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title"><span class="badge badge-red">Thrombocytopénie &lt; 150 000</span></div>
      <ul>
        <li><b>Risque hémorragique significatif &lt; 50 000</b></li>
        <li><b>Hémorragie spontanée &lt; 20 000</b></li>
        <li>Cause centrale : aplasie, chimio/RT, SMD, infiltration tumorale, déficit B12/folates, viroses</li>
        <li>Cause périphérique : PTI auto-immune, médicaments (héparine, pénicillines, phénytoïne, digoxine), hypersplénisme, CIVD</li>
        <li>Miscellanées : hépatopathies, néphropathies, transfusion massive</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-amber">Thrombocytose &gt; 450 000</span></div>
      <ul>
        <li><b>Primaire 30% :</b> thrombocytémie essentielle → risque thrombotique élevé</li>
        <li><b>Réactionnelle 70% :</b> infections, saignement aigu, anémie ferriprive, cancers, lymphomes, maladies inflammatoires (vasculites, MICI), lésions tissulaires (brûlés, IDM, post-splénectomie), exercice intense</li>
      </ul>
    </div>
  </div>

  <div class="subtitle">Les 4 phases de l'hémostase</div>
  <div class="schema">
    <div class="schema-row">
      <div class="schema-box" style="background:#E1F5EE;border-color:#1D9E75;color:#085041;">1 — Hémostase primaire</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Activation → Adhésion (FvW + collagène) → Agrégation (ADP, TxA₂) → Thrombus plaquettaire</span>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#E6F1FB;border-color:#378ADD;color:#0C447C;">2 — Hémostase secondaire</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Cascade coagulation → Protrombine → Trombine → Fibrinogène → Fibrine → coagulum stabilisé</span>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#EEEDFE;border-color:#7F77DD;color:#3C3489;">3 — Mécanismes antitrombotiques</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">Antithrombine · Protéine C · Protéine S → limitent la propagation du caillot</span>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#FAEEDA;border-color:#EF9F27;color:#633806;">4 — Fibrinolyse</div>
      <span class="arrow">→</span>
      <span style="font-size:12px;color:#4a4a4a;">tPA + uPA → Plasminogène → Plasmine → dissolution du caillot → PDF</span>
    </div>
  </div>

  <div class="subtitle">Cascade de coagulation &amp; tests</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Voie extrinsèque → TP</div>
      <ul>
        <li>Déclenchée par le <b>facteur tissulaire</b> (trauma vasculaire)</li>
        <li>VII → VIIa → voie commune</li>
        <li><b>TP allongé :</b> déficit vit K, ACO (Sintrom), hépatopathie, déficit isolé facteur VII</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Voie intrinsèque → TCA</div>
      <ul>
        <li>Activée par contact surface chargée négativement (collagène)</li>
        <li>XII → XI → IX → VIII → voie commune</li>
        <li><b>TCA allongé :</b> héparine non fractionnée, maladie de von Willebrand, hémophilies A/B, syndrome antiphospholipides</li>
      </ul>
    </div>
  </div>
  <div class="alert"><b>Facteurs dépendants de la vitamine K :</b> II, VII, IX, X. Tous synthétisés dans le foie sauf le facteur VIII. Déficit en vit K → TP allongé en premier (facteur VII a la ½ vie la plus courte).</div>

  <div class="subtitle">Maladies hémorragiques — clinique comparative</div>
  <div class="table-wrap">
    <table>
      <tr><th></th><th>Hémostase primaire (plaquettes/vaisseaux)</th><th>Hémostase secondaire (facteurs)</th></tr>
      <tr><td><b>Site saignement</b></td><td>Peau, muqueuses (gingival, nasal, GI, urinaire)</td><td>Tissus profonds, articulations (hémarthroses)</td></tr>
      <tr><td><b>Pétéchies</b></td><td>Présentes</td><td>Absentes</td></tr>
      <tr><td><b>Ecchymoses</b></td><td>Petites, superficielles</td><td>Grandes, palpables, profondes</td></tr>
      <tr><td><b>Hémarthroses</b></td><td>Rares</td><td>Fréquentes</td></tr>
      <tr><td><b>Saignement post-chirurgical</b></td><td>Immédiat, modéré</td><td>Différé, grave</td></tr>
      <tr><td><b>TP / TCA</b></td><td>Normaux</td><td>Allongés (selon la voie atteinte)</td></tr>
    </table>
  </div>

  <div class="subtitle">Hémophilies &amp; maladie de von Willebrand</div>
  <div class="grid3">
    <div class="card">
      <div class="card-title"><span class="badge badge-purple">Hémophilie A</span></div>
      <ul><li>Déficit facteur <b>VIII</b></li><li>Liée au chromosome X</li><li>Fréquence : 1:10 000 (80% des hémophilies)</li><li>Sévérité selon % FVIII : &gt;5% léger, &lt;1% très grave</li><li>TCA allongé, TP normal</li></ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-blue">Hémophilie B</span></div>
      <ul><li>Déficit facteur <b>IX</b></li><li>Liée au chromosome X</li><li>Fréquence : 1:100 000</li><li>Clinique similaire à l'hémophilie A</li><li>TCA allongé, TP normal</li></ul>
    </div>
    <div class="card">
      <div class="card-title"><span class="badge badge-teal">Von Willebrand</span></div>
      <ul><li><b>+ fréquente</b> coagulopathie héréditaire (1:800–1000)</li><li>Autosomique dominante</li><li>FvW : transporteur du FVIII + adhésion plaquettaire</li><li>Déficit hémostase primaire ET secondaire</li></ul>
    </div>
  </div>

  <div class="subtitle">Trastornos acquis de l'hémostase secondaire</div>
  <div class="grid2">
    <div class="card">
      <div class="card-title">Déficit en vitamine K</div>
      <ul>
        <li>Indispensable à la synthèse des facteurs <b>II, VII, IX, X</b></li>
        <li><b>Causes :</b> apport insuffisant, malabsorption intestinale, hépatopathies, médicaments (Sintrom/warfarine)</li>
        <li><b>Diagnostic :</b> TP allongé en premier (facteur VII). Si grave : TP + TCA allongés</li>
        <li><b>Traitement :</b> vitamine K IV ou orale, plasma frais congelé si urgence</li>
      </ul>
    </div>
    <div class="card">
      <div class="card-title">Hépatopathies</div>
      <ul>
        <li>Le foie synthétise <b>tous les facteurs</b> de coagulation sauf le FVIII</li>
        <li>Hépatopathie grave → ↓ production → ↑ risque hémorragique</li>
        <li>Aggravé par : hypersplénisme (↓ plaquettes), varices œsophagiennes</li>
        <li>TP + TCA allongés + thrombocytopénie</li>
      </ul>
    </div>
  </div>

  <div class="subtitle">CIVD — Coagulation intravasculaire disséminée</div>
  <div class="schema">
    <div class="schema-row">
      <div class="schema-box" style="background:#FCEBEB;border-color:#E24B4A;color:#791F1F;">Lésion tissulaire massive / Sepsis / Néoplasie</div>
      <span class="arrow">→</span>
      <div class="schema-box" style="background:#FAEEDA;border-color:#EF9F27;color:#633806;">↑ Facteur tissulaire</div>
      <span class="arrow">→</span>
      <div class="schema-box" style="background:#FAECE7;border-color:#D85A30;color:#712B13;">Thrombose microvasculaire généralisée</div>
    </div>
    <div class="schema-row">
      <div class="schema-box" style="background:#FCEBEB;border-color:#E24B4A;color:#791F1F;">Consommation facteurs + plaquettes</div>
      <span class="arrow">+</span>
      <div class="schema-box" style="background:#FCEBEB;border-color:#E24B4A;color:#791F1F;">Fibrinolyse secondaire</div>
      <span class="arrow">→</span>
      <div class="schema-box" style="background:#FCEBEB;border-color:#E24B4A;color:#791F1F;">Hémorragie paradoxale</div>
    </div>
  </div>
  <div class="danger"><b>Biologie CIVD :</b> TP et TCA allongés + thrombocytopénie + ↑ D-dimères + ↓ fibrinogène. Urgence médicale absolue.</div>
</div>

<!-- DIAGNOSTIC -->
<div id="diagnostic" class="section">
  <div class="highlight"><b>Démarche diagnostique devant une anémie :</b> partir toujours du VCM, puis des réticulocytes, puis du profil martial ou de la moelle selon l'orientation.</div>

  <div class="subtitle">Arbre décisionnel des anémies</div>
  <div class="schema" style="padding:1.25rem;">
    <div style="text-align:center;margin-bottom:14px;">
      <div class="tree-node" style="background:#EEEDFE;border-color:#7F77DD;color:#3C3489;font-size:13px;padding:7px 18px;">Anémie confirmée (Hb ↓ + VCM mesuré)</div>
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px;margin-bottom:12px;">
      <div style="text-align:center;">
        <div class="tree-node" style="background:#FAECE7;border-color:#D85A30;color:#712B13;">VCM &lt; 80 fl<br><span style="font-weight:400;font-size:11px;">Microcytaire</span></div>
        <div style="font-size:11px;color:#4a4a4a;margin-top:6px;line-height:1.7;">→ Profil martial<br>Ferritine ↓ + transferrine ↑ :<br><b>ferriprive</b><br>Ferritine N/↑ :<br><b>thalassémie</b> (électrophorèse Hb)</div>
      </div>
      <div style="text-align:center;">
        <div class="tree-node" style="background:#E1F5EE;border-color:#1D9E75;color:#085041;">VCM 80–100 fl<br><span style="font-weight:400;font-size:11px;">Normocytaire</span></div>
        <div style="font-size:11px;color:#4a4a4a;margin-top:6px;line-height:1.7;">→ Réticulocytes<br>↑ : saignement aigu<br>↓ ou N → profil martial<br>Fe↓ + ferritine↑ : <b>ATC</b><br>Ferritine↓ : <b>ferriprive phase 2</b><br>Aplasie/SMD → <b>BOM</b></div>
      </div>
      <div style="text-align:center;">
        <div class="tree-node" style="background:#EEEDFE;border-color:#7F77DD;color:#3C3489;">VCM &gt; 100 fl<br><span style="font-weight:400;font-size:11px;">Macrocytaire</span></div>
        <div style="font-size:11px;color:#4a4a4a;margin-top:6px;line-height:1.7;">→ Réticulocytes<br>↑ : hémolyse (LDH↑, bili↑, haptoglobine↓)<br>↓ ou N → frottis SP<br>Hypersegmentation neutrophiles :<br><b>B12/folates ↓</b><br>Altérations morphos → <b>BOM</b></div>
      </div>
    </div>
  </div>

  <div class="subtitle">Bilan des troubles de la coagulation</div>
  <div class="table-wrap">
    <table>
      <tr><th>TP</th><th>TCA</th><th>Causes principales</th></tr>
      <tr><td><b>Allongé</b></td><td>Normal</td><td>Déficit facteur VII · Déficit vitamine K (précoce) · ACO (warfarine, Sintrom) · Inhibiteur du facteur VII</td></tr>
      <tr><td>Normal</td><td><b>Allongé</b></td><td>Hémophilie A (FVIII) · Hémophilie B (FIX) · Maladie de von Willebrand · Héparine non fractionnée · Syndrome antiphospholipides</td></tr>
      <tr><td><b>Allongé</b></td><td><b>Allongé</b></td><td>Déficit vitamine K sévère · Hépatopathie grave · CIVD · Déficit protrombine / fibrinogène / facteurs V ou X</td></tr>
      <tr><td>Normal</td><td>Normal</td><td>Trouble hémostase primaire (plaquettes ou vaisseaux). Vérifier : NFS plaquettes + temps de saignement</td></tr>
    </table>
  </div>

  <div class="subtitle">Résumé comparatif de toutes les anémies</div>
  <div class="table-wrap">
    <table>
      <tr><th>Type d'anémie</th><th>VCM</th><th>Réticulocytes</th><th>Marqueurs clés</th></tr>
      <tr><td><b>Ferriprive</b></td><td>↓ &lt;80</td><td>↓</td><td>Ferritine ↓, transferrine ↑, fer ↓</td></tr>
      <tr><td><b>Thalassémie</b></td><td>↓ &lt;80</td><td>Variable</td><td>Ferritine N/↑, électrophorèse Hb anormale</td></tr>
      <tr><td><b>Maladies chroniques</b></td><td>N (80–100)</td><td>↓</td><td>Ferritine N/↑, fer ↓, transferrine ↓</td></tr>
      <tr><td><b>IRC</b></td><td>N (80–100)</td><td>↓</td><td>EPO insuffisante</td></tr>
      <tr><td><b>Aplasie médullaire</b></td><td>N/↑</td><td>↓↓</td><td>Pancytopénie, BOM : moelle pauvre</td></tr>
      <tr><td><b>Mégaloblastique (B12/folates)</b></td><td>↑ &gt;100</td><td>↓</td><td>B12↓ et/ou folates↓, hypersegmentation neutrophiles</td></tr>
      <tr><td><b>Hémolytique</b></td><td>↑ (réticulocytes)</td><td>↑↑</td><td>LDH ↑, bilirubine indirecte ↑, haptoglobine ↓</td></tr>
      <tr><td><b>Saignement aigu</b></td><td>N (80–100)</td><td>↑ (après 24–48h)</td><td>Contexte clinique évident</td></tr>
    </table>
  </div>
</div>

<!-- QUIZ -->
<div id="quiz" class="section">
  <div class="highlight">10 questions couvrant l'ensemble du cours. Cliquez sur une réponse pour vérifier.</div>
  <div class="score-box">
    <div class="score-num" id="score-display">0 / 10</div>
    <div class="score-label">Score en cours<br><span style="font-size:12px;">Se met à jour après chaque réponse</span></div>
    <button class="reset-all-btn" onclick="resetAll()">Tout réinitialiser</button>
  </div>

  <div class="quiz-card" id="q1">
    <div class="quiz-q">1. Quel est le seuil d'hémoglobine définissant l'anémie chez l'homme adulte ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q1',this,false,'Non. 12 g/dl est le seuil chez la femme.')">12 g/dl</button>
      <button class="quiz-opt" onclick="answer('q1',this,true,'Correct ! Hb &lt; 13 g/dl chez l\'homme, &lt; 12 g/dl chez la femme, &lt; 11 g/dl chez la femme enceinte.')">13 g/dl</button>
      <button class="quiz-opt" onclick="answer('q1',this,false,'Non. 11 g/dl est le seuil chez la femme enceinte.')">11 g/dl</button>
      <button class="quiz-opt" onclick="answer('q1',this,false,'Non. Ce seuil n\'est pas utilisé en clinique.')">10 g/dl</button>
    </div>
    <div class="quiz-feedback" id="q1-fb"></div>
    <button class="reset-btn" id="q1-reset" onclick="resetQ('q1')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q2">
    <div class="quiz-q">2. Quelle anémie présente un VCM &lt; 80 fl, une ferritine basse et une transferrine élevée ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q2',this,false,'Non. L\'anémie pernicieuse est macrocytaire (déficit B12).')">Anémie pernicieuse</button>
      <button class="quiz-opt" onclick="answer('q2',this,false,'Non. L\'anémie hémolytique est régénérative avec réticulocytes élevés.')">Anémie hémolytique</button>
      <button class="quiz-opt" onclick="answer('q2',this,true,'Correct ! L\'anémie ferriprive est microcytaire hyporégénérative : ferritine ↓, transferrine ↑, fer ↓.')">Anémie ferriprive</button>
      <button class="quiz-opt" onclick="answer('q2',this,false,'Non. L\'aplasie médullaire entraîne une pancytopénie avec VCM souvent normal.')">Aplasie médullaire</button>
    </div>
    <div class="quiz-feedback" id="q2-fb"></div>
    <button class="reset-btn" id="q2-reset" onclick="resetQ('q2')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q3">
    <div class="quiz-q">3. Quelle est la principale différence entre le déficit en B12 et le déficit en folates ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q3',this,false,'Non. Les deux donnent une macrocytose et une pancytopénie potentielle.')">Le déficit en folates donne une microcytose</button>
      <button class="quiz-opt" onclick="answer('q3',this,true,'Correct ! Seul le déficit en B12 entraîne des signes neurologiques (démyélinisation, ataxie, démence). Le déficit en folates n\'en provoque pas.')">Seul le déficit en B12 entraîne des signes neurologiques</button>
      <button class="quiz-opt" onclick="answer('q3',this,false,'Non. Les deux entraînent une anémie macrocytaire.')">Seul le déficit en folates donne une anémie</button>
      <button class="quiz-opt" onclick="answer('q3',this,false,'Non. Les deux peuvent donner une pancytopénie.')">Le déficit en B12 ne donne jamais de pancytopénie</button>
    </div>
    <div class="quiz-feedback" id="q3-fb"></div>
    <button class="reset-btn" id="q3-reset" onclick="resetQ('q3')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q4">
    <div class="quiz-q">4. En dessous de quel seuil de neutrophiles faut-il obligatoirement hospitaliser en cas d'infection ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q4',this,false,'Non. Entre 500 et 1 000, un traitement ambulatoire peut être envisagé.')">1 000/µl</button>
      <button class="quiz-opt" onclick="answer('q4',this,true,'Correct ! &lt; 500/µl = risque élevé → hospitalisation obligatoire si infection.')">500/µl</button>
      <button class="quiz-opt" onclick="answer('q4',this,false,'Non. &lt; 1 500 = risque très faible.')">1 500/µl</button>
      <button class="quiz-opt" onclick="answer('q4',this,false,'Non. &lt; 200 = risque très élevé, mais la borne clé est &lt; 500.')">200/µl</button>
    </div>
    <div class="quiz-feedback" id="q4-fb"></div>
    <button class="reset-btn" id="q4-reset" onclick="resetQ('q4')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q5">
    <div class="quiz-q">5. Quels facteurs de coagulation dépendent de la vitamine K ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q5',this,false,'Non. Les facteurs I et V ne dépendent pas de la vitamine K.')">I, V, VIII, X</button>
      <button class="quiz-opt" onclick="answer('q5',this,true,'Correct ! Les facteurs II, VII, IX et X sont dépendants de la vitamine K. Le facteur VII a la ½ vie la plus courte → TP allongé en premier.')">II, VII, IX, X</button>
      <button class="quiz-opt" onclick="answer('q5',this,false,'Non. Le facteur VIII est synthétisé hors du foie et ne dépend pas de la vit K.')">VIII, IX, XI, XII</button>
      <button class="quiz-opt" onclick="answer('q5',this,false,'Non.')">III, VII, X, XI</button>
    </div>
    <div class="quiz-feedback" id="q5-fb"></div>
    <button class="reset-btn" id="q5-reset" onclick="resetQ('q5')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q6">
    <div class="quiz-q">6. Quelle est la coagulopathie héréditaire la plus fréquente ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q6',this,false,'Non. L\'hémophilie A (déficit FVIII), fréquence 1:10 000.')">Hémophilie A</button>
      <button class="quiz-opt" onclick="answer('q6',this,false,'Non. L\'hémophilie B est encore plus rare (1:100 000).')">Hémophilie B</button>
      <button class="quiz-opt" onclick="answer('q6',this,true,'Correct ! La maladie de von Willebrand est la + fréquente (1:800–1000), autosomique dominante. Le FvW assure le transport du FVIII et l\'adhésion plaquettaire.')">Maladie de von Willebrand</button>
      <button class="quiz-opt" onclick="answer('q6',this,false,'Non.')">Déficit en facteur VII</button>
    </div>
    <div class="quiz-feedback" id="q6-fb"></div>
    <button class="reset-btn" id="q6-reset" onclick="resetQ('q6')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q7">
    <div class="quiz-q">7. Quelle est la cause principale d'une polyglobulie avec un taux d'EPO bas ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q7',this,false,'Non. L\'IRC entraîne une anémie (EPO insuffisante), pas une polyglobulie.')">Insuffisance rénale chronique</button>
      <button class="quiz-opt" onclick="answer('q7',this,false,'Non. Le tabagisme provoque une polyglobulie secondaire (réactionnelle à l\'hypoxie) avec EPO élevée.')">Tabagisme chronique</button>
      <button class="quiz-opt" onclick="answer('q7',this,true,'Correct ! La polycythémie vraie (Vaquez) est une hémopathie maligne myéloproliférative où la production d\'hématies est autonome → EPO basse par rétrocontrôle. Mutation JAK2 dans &gt;95% des cas.')">Polycythémie vraie (Vaquez)</button>
      <button class="quiz-opt" onclick="answer('q7',this,false,'Non. L\'altitude élevée provoque une polyglobulie secondaire (EPO élevée réactionnelle à l\'hypoxie).')">Altitude élevée</button>
    </div>
    <div class="quiz-feedback" id="q7-fb"></div>
    <button class="reset-btn" id="q7-reset" onclick="resetQ('q7')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q8">
    <div class="quiz-q">8. Dans l'anémie des maladies chroniques, quel mécanisme explique l'inhibition de l'érythropoïèse ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q8',this,false,'Non. La carence en fer alimentaire est la cause de l\'anémie ferriprive.')">Carence en fer alimentaire</button>
      <button class="quiz-opt" onclick="answer('q8',this,true,'Correct ! L\'inflammation chronique active les macrophages et lymphocytes T qui libèrent IL-1 et TNF → inhibition de l\'érythropoïèse. La ferritine est normale ou élevée (le fer est séquestré).')">Libération d'IL-1 et TNF par les macrophages activés</button>
      <button class="quiz-opt" onclick="answer('q8',this,false,'Non. La destruction des cellules pariétales entraîne un déficit en facteur intrinsèque → anémie pernicieuse.')">Destruction des cellules pariétales gastriques</button>
      <button class="quiz-opt" onclick="answer('q8',this,false,'Non. Ce mécanisme correspond à la polycythémie vraie.')">Mutation autonome du clone médullaire</button>
    </div>
    <div class="quiz-feedback" id="q8-fb"></div>
    <button class="reset-btn" id="q8-reset" onclick="resetQ('q8')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q9">
    <div class="quiz-q">9. Un patient présente des hémarthroses récidivantes avec un TCA allongé et un TP normal. Quel diagnostic évoquer ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q9',this,false,'Non. Le PTI entraîne une thrombocytopénie avec TP et TCA normaux, et des saignements muqueux/cutanés.')">Purpura thrombocytopénique idiopathique</button>
      <button class="quiz-opt" onclick="answer('q9',this,false,'Non. La maladie de von Willebrand touche surtout les muqueuses (hémostase primaire).')">Maladie de von Willebrand</button>
      <button class="quiz-opt" onclick="answer('q9',this,true,'Correct ! Les hémarthroses + TCA allongé + TP normal orientent vers une hémophilie A (déficit FVIII) ou B (déficit FIX), maladies de la voie intrinsèque.')">Hémophilie A ou B</button>
      <button class="quiz-opt" onclick="answer('q9',this,false,'Non. Le déficit en vit K allonge le TP en premier (voie extrinsèque), pas le TCA isolément.')">Déficit en vitamine K</button>
    </div>
    <div class="quiz-feedback" id="q9-fb"></div>
    <button class="reset-btn" id="q9-reset" onclick="resetQ('q9')">Réinitialiser</button>
  </div>

  <div class="quiz-card" id="q10">
    <div class="quiz-q">10. Quels marqueurs biologiques caractérisent une anémie hémolytique ?</div>
    <div class="quiz-opts">
      <button class="quiz-opt" onclick="answer('q10',this,false,'Non. Ces marqueurs correspondent à l\'anémie ferriprive.')">Ferritine ↓, transferrine ↑, TP normal</button>
      <button class="quiz-opt" onclick="answer('q10',this,false,'Non. Ces marqueurs correspondent à une anémie mégaloblastique.')">VCM &gt; 100, pancytopénie, B12 basse</button>
      <button class="quiz-opt" onclick="answer('q10',this,true,'Correct ! L\'hémolyse libère le contenu des hématies : LDH ↑ + bilirubine indirecte ↑ + haptoglobine ↓ (consommée par l\'Hb libre) + réticulocytes ↑ (anémie régénérative).')">LDH ↑, bilirubine indirecte ↑, haptoglobine ↓, réticulocytes ↑</button>
      <button class="quiz-opt" onclick="answer('q10',this,false,'Non. TP et TCA allongés correspondent à des troubles de la coagulation, pas à une hémolyse.')">TP et TCA allongés, thrombocytopénie</button>
    </div>
    <div class="quiz-feedback" id="q10-fb"></div>
    <button class="reset-btn" id="q10-reset" onclick="resetQ('q10')">Réinitialiser</button>
  </div>
</div>

</div>
<script>
var scores={};
function showSection(id,btn){
  document.querySelectorAll('.section').forEach(function(s){s.classList.remove('visible');});
  document.querySelectorAll('.nav-btn').forEach(function(b){b.classList.remove('active');});
  document.getElementById(id).classList.add('visible');
  btn.classList.add('active');
}
function updateScore(){
  var c=Object.values(scores).filter(function(v){return v;}).length;
  document.getElementById('score-display').textContent=c+' / 10';
}
function answer(qid,btn,isCorrect,explanation){
  var card=document.getElementById(qid);
  if(card.dataset.answered)return;
  card.dataset.answered='true';
  scores[qid]=isCorrect;
  card.querySelectorAll('.quiz-opt').forEach(function(o){o.style.pointerEvents='none';});
  btn.classList.add(isCorrect?'correct':'wrong');
  var fb=document.getElementById(qid+'-fb');
  fb.textContent=explanation;
  fb.className='quiz-feedback show '+(isCorrect?'feedback-ok':'feedback-ko');
  document.getElementById(qid+'-reset').classList.add('show');
  updateScore();
}
function resetQ(qid){
  var card=document.getElementById(qid);
  delete card.dataset.answered;
  delete scores[qid];
  card.querySelectorAll('.quiz-opt').forEach(function(o){o.classList.remove('correct','wrong');o.style.pointerEvents='';});
  document.getElementById(qid+'-fb').className='quiz-feedback';
  document.getElementById(qid+'-reset').classList.remove('show');
  updateScore();
}
function resetAll(){for(var i=1;i<=10;i++){resetQ('q'+i);}}
</script>
</body>
</html>
