<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>海尔 14.5L 炸烤一体机食谱</title>
<meta name="theme-color" content="#2563eb">
<link rel="manifest" href="data:application/json;base64,eyJuYW1lIjoi5aW95LqsIOi9veWKoOWGteW3peS4quS6pCIsInNob3J0X25hbWUiOiLlt7rkuK3lj5kiLCJzdGFydF91cmwiOiIiLCJkaXNwbGF5Ijoic3RhbmRhbG9uZSIsImJhY2tncm91bmRfY29sb3IiOiIjZjdmN2Y3NyIsInRoZW1lX2NvbG9yIjoiIzI1NjNlYiJ9">
<style>
*{box-sizing:border-box;margin:0;padding:0;font-family:system-ui,sans-serif}
body{padding:16px;background:#f7f7f7}
h1{text-align:center;margin-bottom:16px;font-size:22px;color:#1f2937}
.search-box{width:100%;padding:12px;font-size:16px;border:1px solid #ccc;border-radius:12px;margin-bottom:14px}
.btns{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;margin-bottom:22px}
.btn{padding:10px 14px;border:none;border-radius:999px;color:white;font-size:15px;cursor:pointer;transition:0.2s}
.btn.all{background:#6b7280}
.btn.fit{background:#22c55e}
.btn.kid{background:#fb923c}
.btn.family{background:#2563eb}
.btn.active{filter:saturate(130%);transform:scale(1.03);font-weight:bold}
.btn:hover{opacity:0.85}

.category-title{margin:26px 0 10px 0;font-size:18px;font-weight:bold;color:#1f2937;border-left:4px solid #2563eb;padding-left:10px}
table{width:100%;border-collapse:collapse;background:white;border-radius:12px;overflow:hidden;margin-bottom:14px}
th,td{border:1px solid #e5e7eb;padding:11px;text-align:left;font-size:14px}
th{background:#eef2ff}
tr{cursor:pointer}
tr:hover{background:#f0f7ff}

.modal-wrap{position:fixed;inset:0;background:rgba(0,0,0,0.55);display:none;align-items:center;justify-content:center;padding:16px;z-index:999}
.modal{background:#fff;border-radius:18px;max-width:620px;width:100%;max-height:86vh;overflow-y:auto;padding:22px}
.modal h2{margin-bottom:14px;color:#1f2937}
.modal h3{margin:12px 0 6px;color:#2563eb;font-size:17px}
.modal p, .modal li{font-size:14px;line-height:1.65}
.modal ul, .modal ol{padding-left:22px;margin-bottom:12px}
.modal-close{margin-top:18px;width:100%;padding:11px;border:none;border-radius:999px;background:#2563eb;color:white;font-size:15px;cursor:pointer}

@media(max-width:720px){
  table, thead, tbody, th, td, tr { display:block }
  thead{display:none}
  tr{margin-bottom:14px;border:1px solid #ddd;border-radius:12px;background:white;padding:10px}
  td{display:flex;padding:7px;gap:8px}
  td::before{font-weight:bold;width:72px}
  td:nth-child(1)::before{content:"菜品:"}
  td:nth-child(2)::before{content:"模式:"}
  td:nth-child(3)::before{content:"温度:"}
  td:nth-child(4)::before{content:"时间:"}
  td:nth-child(5)::before{content:"备注:"}
}
</style>
</head>
<body>
<h1>海尔 14.5L 炸烤一体机食谱查询</h1>
<input class="search-box" id="searchInput" placeholder="🔍 输入菜名 / 食材 / 分类，例如：鸡蛋、虾、番薯" oninput="doSearch()">
<div class="btns">
  <button class="btn all active" data-tag="all" onclick="setTag('all')">全部食谱</button>
  <button class="btn fit" data-tag="fit" onclick="setTag('fit')">健身餐</button>
  <button class="btn kid" data-tag="kid" onclick="setTag('kid')">儿童餐</button>
  <button class="btn family" data-tag="family" onclick="setTag('family')">全家餐</button>
</div>
<div id="container"></div>

<div class="modal-wrap" id="modalWrap" onclick="closeModalByBg(event)">
  <div class="modal" onclick="event.stopPropagation()">
    <h2 id="modalTitle"></h2>
    <div id="modalBody"></div>
    <button class="modal-close" onclick="closeModal()">关闭</button>
  </div>
</div>

<script>
let currentTag = "all";
let keyword = "";

const data = [
  {
    category:"鸡肉",
    name:"健身鸡胸肉",
    tag:["fit"],
    mode:"Air Fry",
    temp:"170°C",
    time:"12–15 min",
    note:"切薄腌制；中途翻面；中心温度 75°C；不要烤太久，避免肉质干柴；少油少盐",
    ingredients:"鸡胸肉 150g，少许海盐、黑胡椒，几滴橄榄油",
    steps:["鸡胸切薄片，用盐、黑胡椒、橄榄油抓匀腌 15 分钟","平铺放在烤架，不要重叠","170°C，烤到一半取出翻面","出炉静置 3 分钟再切，锁住肉汁"]
  },
  {
    category:"鸡肉",
    name:"盐焗鸡块（小块）",
    tag:["kid","family"],
    mode:"Air Fry",
    temp:"175°C",
    time:"20 min",
    note:"盐焗粉腌至少一小时；中途翻面；大块鸡肉增加时间；适合小朋友，味道温和",
    ingredients:"鸡肉块 200g，盐焗粉少许",
    steps:["鸡肉洗净吸干水分，拌入盐焗粉腌 60 分钟","摆上烤架，分散摆放","175°C，烤至一半翻面","烤到鸡肉熟透即可"]
  },
  {
    category:"鸡肉",
    name:"香烤去骨鸡腿",
    tag:["kid","family","fit"],
    mode:"Air Fry",
    temp:"175°C",
    time:"18 min",
    note:"去皮就是健身版本；腌料只用少许盐、胡椒；中途翻面；表皮微焦即可；带皮更香，但油脂较高",
    ingredients:"去骨鸡腿一只，海盐、黑胡椒少许",
    steps:["鸡腿洗净吸干；想要健身版去掉鸡皮","撒盐与黑胡椒腌 20 分钟","放烤架，175°C，中途翻面","烤至表皮微焦，肉完全熟透"]
  },
  {
    category:"鸡肉",
    name:"奥尔良烤翅",
    tag:["family","kid"],
    mode:"Air Fry",
    temp:"180°C",
    time:"16 min",
    note:"提前腌 2 小时；中途翻面；喜欢多汁可以喷一点点水；健身少吃，酱料糖分偏高",
    ingredients:"鸡翅 6 只，奥尔良腌料",
    steps:["鸡翅划两刀，拌腌料冷藏腌 2 小时以上","平铺烤架，不要堆叠","180°C，烤至一半翻面","喜欢多汁中途轻喷一点清水"]
  },
  {
    category:"牛肉",
    name:"烤瘦牛肉薄片（健身）",
    tag:["fit"],
    mode:"Air Fry",
    temp:"165°C",
    time:"5–7 min",
    note:"选瘦牛里脊；切薄；黑胡椒 + 少量盐；不要烤过头，容易老；适合搭配烤蔬菜",
    ingredients:"牛里脊薄片 120g，海盐、黑胡椒",
    steps:["牛肉切薄片，吸干水分，撒盐和黑胡椒","平铺烤架，单层摆放","165°C，时间不要过长","微微变色立刻取出，避免变老"]
  },
  {
    category:"牛肉",
    name:"烤牛肉丸",
    tag:["kid","family"],
    mode:"Air Fry",
    temp:"165°C",
    time:"10 min",
    note:"冷冻无需解冻；中途翻面；小朋友很喜欢；留意市售丸子钠偏高",
    ingredients:"牛肉丸 6–8 颗",
    steps:["冷冻丸子不用解冻，表面轻划一刀","放烤架分散开","165°C，中途翻面","烤到表面鼓起微微焦香"]
  },
  {
    category:"猪肉",
    name:"烤瘦五花肉（低脂版）",
    tag:["family","fit"],
    mode:"Air Fry",
    temp:"170°C",
    time:"14 min",
    note:"尽量切掉多余肥油；切薄片；少量海盐；中途翻面；出油多，可以垫油纸吸油",
    ingredients:"瘦五花肉 150g，海盐少许",
    steps:["切除多余肥肉，切薄片，撒盐腌一会儿","铺烤架，下方可以放油纸接油","170°C，中途翻面","烤到边缘微卷即可"]
  },
  {
    category:"猪肉",
    name:"烤猪肉肠",
    tag:["kid","family"],
    mode:"Air Fry",
    temp:"160°C",
    time:"9 min",
    note:"表面划刀；中途翻面；儿童款尽量挑选少盐无添加香肠",
    ingredients:"儿童猪肉肠 3–4 根",
    steps:["香肠表面轻轻划几道小口","摆上烤架","160°C，中途翻面","烤到微微鼓起、香气出来"]
  },
  {
    category:"海鲜鱼虾",
    name:"香烤虾仁",
    tag:["fit","kid","family"],
    mode:"Air Fry",
    temp:"160°C",
    time:"6–8 min",
    note:"虾仁去线吸干；不要烤太久；健身优选高蛋白；小朋友适合",
    ingredients:"虾仁 150g，少许盐、黑胡椒",
    steps:["虾仁去虾线，吸干水分，撒盐黑胡椒","单层摆放烤架","160°C，烤到虾仁卷曲变色","避免烤干"]
  },
  {
    category:"海鲜鱼虾",
    name:"烤巴沙鱼柳",
    tag:["fit","kid"],
    mode:"Air Fry",
    temp:"160°C",
    time:"10 min",
    note:"无刺适合小孩；健身低脂；容易碎，不要频繁翻动",
    ingredients:"巴沙鱼柳一块，少许盐、柠檬汁",
    steps:["鱼柳吸干，撒盐、滴几滴柠檬汁","放烤盘，不要堆叠","160°C，烤至鱼肉变白熟透","小心取出，鱼肉软容易散"]
  },
  {
    category:"鸡蛋",
    name:"槟城 Kopitiam 半生熟蛋",
    tag:["fit","family"],
    mode:"Air Fry",
    temp:"150°C",
    time:"6 min",
    note:"鸡蛋回室温，放烤架；火力猛改用 140°C；蛋大可拉到 6.5 min；冰箱冷蛋 150°C / 7 min（易爆）；出炉静置 1 min，不用冰水；配甜黑豉油 + 白胡椒；不用翻面",
    ingredients:"常温鸡蛋 1–2 颗，甜黑豉油、白胡椒",
    steps:["鸡蛋放到室温，直接摆在烤架上","150°C，计时 6 分钟","取出静置一分钟，不要泡冰水","敲开，加入甜黑豉油与白胡椒拌匀"]
  },
  {
    category:"鸡蛋",
    name:"家常水浴蒸蛋",
    tag:["fit","kid","family"],
    mode:"Air Fry",
    temp:"130°C",
    time:"18 min，焖 3 min",
    note:"蛋液:温水 = 1:2；想要更嫩用 1:2.2；温水约 40°C；过筛去泡沫；碗封锡纸留缝；下层烤盘加热水至碗身一半；大碗加到 22 min；火力猛改用 120°C / 20 min；健身版少盐，不加香油",
    ingredients:"鸡蛋 2 颗，温水，少许盐",
    steps:["鸡蛋打散，加入温水、少量盐搅匀","过筛去掉泡沫，倒入碗里","封锡纸，扎小孔；下层烤盘加水水浴","130°C，烤完焖 3 分钟再取出"]
  },
  {
    category:"鸡蛋",
    name:"日式茶碗蒸（水浴）",
    tag:["family"],
    mode:"Air Fry",
    temp:"130°C",
    time:"22 min，焖 3 min",
    note:"蛋液:Dashi = 1:2.5；极嫩版本 1:3；出汁 40°C；过筛；锡纸留缝；水浴；可加虾仁、香菇、鱼板；量大调到 28 min；火力猛改用 120°C / 24 min",
    ingredients:"鸡蛋 2 颗，日式出汁，虾仁、香菇少许",
    steps:["鸡蛋打散，混入出汁搅匀，过筛","放入虾仁香菇，封锡纸扎孔","下层加水做水浴","130°C，烤好焖 3 分钟取出"]
  },
  {
    category:"鸡蛋",
    name:"烤荷包蛋",
    tag:["fit","kid"],
    mode:"Air Fry",
    temp:"150°C",
    time:"7 min",
    note:"小碗刷薄油打入鸡蛋；喜欢流心缩短到 6 分钟；全熟加到 8 分钟",
    ingredients:"鸡蛋 1 颗，少许油",
    steps:["小碗薄薄刷一层油，打入鸡蛋","放入炸烤一体机","150°C，按喜好控制时间取出"]
  },
  {
    category:"豆制品",
    name:"香烤老豆腐",
    tag:["fit","kid","family"],
    mode:"Air Fry",
    temp:"170°C",
    time:"12 min",
    note:"老豆腐不容易碎；表面喷一点点油；中途翻面；健身优质植物蛋白",
    ingredients:"老豆腐一块，海盐、黑胡椒少许",
    steps:["豆腐切厚片，吸干表面水分","轻喷少许油，撒盐胡椒","单层放烤架，170°C，中途翻面","烤至表面金黄起壳"]
  },
  {
    category:"根茎碳水",
    name:"烤番薯",
    tag:["fit","kid","family"],
    mode:"Air Fry",
    temp:"180°C",
    time:"25–35 min",
    note:"小番薯时间短；大颗要久一点；可以直接作为健身主食；无需加糖",
    ingredients:"番薯 1–2 条",
    steps:["番薯洗净擦干，不用去皮","放烤架","180°C，中途翻面；用牙签戳得透就是熟了"]
  },
  {
    category:"根茎碳水",
    name:"烤玉米",
    tag:["fit","kid","family"],
    mode:"Air Fry",
    temp:"175°C",
    time:"14 min",
    note:"新鲜玉米；喜欢奶香可以刷一点点淡奶；健身直接原味",
    ingredients:"甜玉米一条",
    steps:["玉米剥好洗净吸干","放烤架","175°C，中途翻面，烤到颗粒微微焦香"]
  },
  {
    category:"蔬菜",
    name:"烤西兰花",
    tag:["fit","kid","family"],
    mode:"Air Fry",
    temp:"170°C",
    time:"10 min",
    note:"不要烤太久，不然发黄发苦；少油；健身标配配菜",
    ingredients:"西兰花一小颗，少许盐、橄榄油",
    steps:["西兰花切小朵，洗净吸干","拌一点点油、盐","平铺烤架，170°C；中途轻晃烤架"]
  },
  {
    category:"面点速冻",
    name:"烤包子（复热）",
    tag:["family","kid"],
    mode:"Air Fry",
    temp:"160°C",
    time:"7–9 min",
    note:"冷冻包子直接烤；表面喷一点水，外皮不会干硬",
    ingredients:"冷冻包子 2–3 个",
    steps:["包子不用解冻，表面轻喷清水","摆上烤架分开摆放","160°C，烤到外皮松软温热"]
  },
  {
    category:"烤水果",
    name:"烤凤梨",
    tag:["family","kid"],
    mode:"Air Fry",
    temp:"160°C",
    time:"8 min",
    note:"烤过后甜味更突出；可以当加餐，不用额外加糖",
    ingredients:"凤梨块适量",
    steps:["凤梨切小块，吸干汁水","单层摆放烤架","160°C，烤至边缘微微焦香"]
  },
  {
    category:"甜品",
    name:"烤香蕉",
    tag:["family","kid","fit"],
    mode:"Air Fry",
    temp:"165°C",
    time:"9 min",
    note:"熟透香蕉最好；天然甜，适合健身加餐；可以撒一点点肉桂粉",
    ingredients:"香蕉一条",
    steps:["香蕉剥皮或者保留薄皮；切段","放烤架","165°C，烤到变软香气出来"]
  }
];

function render(){
  const container = document.getElementById("container");
  container.innerHTML = "";
  let filtered = data.filter(item=>{
    const matchTag = (currentTag === "all") || item.tag.includes(currentTag);
    const text = (item.category + " " + item.name + " " + item.note + " " + item.ingredients + " " + item.steps.join(" ")).toLowerCase();
    const matchKey = keyword === "" || text.includes(keyword.toLowerCase());
    return matchTag && matchKey;
  });
  const groups = {};
  filtered.forEach(d=>{
    if(!groups[d.category]) groups[d.category] = [];
    groups[d.category].push(d);
  });
  for(const cat in groups){
    const h = document.createElement("div");
    h.className = "category-title";
    h.innerText = cat;
    container.appendChild(h);
    const table = document.createElement("table");
    const thead = document.createElement("thead");
    thead.innerHTML = `<tr><th>菜品</th><th>模式</th><th>温度</th><th>时间</th><th>备注</th></tr>`;
    table.appendChild(thead);
    const tbody = document.createElement("tbody");
    groups[cat].forEach(rec=>{
      const tr = document.createElement("tr");
      tr.innerHTML = `<td>${rec.name}</td><td>${rec.mode}</td><td>${rec.temp}</td><td>${rec.time}</td><td>${rec.note}</td>`;
      tr.onclick = ()=>openModal(rec);
      tbody.appendChild(tr);
    });
    table.appendChild(tbody);
    container.appendChild(table);
  }
}

function setTag(t){
  currentTag = t;
  document.querySelectorAll(".btn").forEach(b=>{
    b.classList.remove("active");
    if(b.dataset.tag === t) b.classList.add("active");
  });
  render();
}

function doSearch(){
  keyword = document.getElementById("searchInput").value.trim();
  render();
}

function openModal(rec){
  document.getElementById("modalTitle").innerText = rec.name;
  let html = `<h3>🍳 参数</h3>
  <p>模式：${rec.mode}｜温度：${rec.temp}｜时间：${rec.time}</p>
  <h3>🥬 食材</h3>
  <p>${rec.ingredients}</p>
  <h3>📝 步骤</h3><ol>`;
  rec.steps.forEach(s=> html += `<li>${s}</li>`);
  html += `</ol><h3>💡 小贴士</h3><p>${rec.note}</p>`;
  document.getElementById("modalBody").innerHTML = html;
  document.getElementById("modalWrap").style.display = "flex";
}

function closeModal(){
  document.getElementById("modalWrap").style.display = "none";
}
function closeModalByBg(e){
  if(e.target.id === "modalWrap") closeModal();
}

render();
</script>
</body>
</html>
