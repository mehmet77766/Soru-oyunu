# Soru-oyunu
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Sevgilime Özel Soru Oyunu</title>
<style>
  body {
    background: #4b0082;
    color: #f0e6ff;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; padding: 0;
    display: flex; justify-content: center; align-items: center;
    height: 100vh;
  }
  #game-container {
    background: #5a189a;
    padding: 20px 30px;
    border-radius: 15px;
    width: 90%;
    max-width: 500px;
    box-shadow: 0 0 15px #9d4edd;
  }
  h1 {
    text-align: center;
    margin-bottom: 15px;
  }
  #question {
    font-size: 1.3rem;
    margin-bottom: 20px;
  }
  .option-btn {
    display: block;
    background: #7b2ff7;
    border: none;
    border-radius: 10px;
    color: white;
    padding: 12px 20px;
    margin: 10px 0;
    font-size: 1rem;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  .option-btn:hover {
    background: #9d4edd;
  }
  #next-btn {
    background: #9d4edd;
    margin-top: 20px;
    padding: 12px 0;
    width: 100%;
    border: none;
    border-radius: 10px;
    font-size: 1.2rem;
    cursor: pointer;
    display: none;
  }
  #score-container {
    text-align: center;
  }
  #score {
    font-size: 1.6rem;
    margin: 15px 0;
  }
  #result-message {
    font-size: 1.2rem;
    margin-top: 10px;
    color: #dcd6f7;
  }
</style>
</head>
<body>

<div id="game-container">
  <h1>Sevgilime Özel Soru Oyunu</h1>
  <div id="question"></div>
  <div id="options-container"></div>
  <button id="next-btn">Sonraki Soru</button>
  <div id="score-container" style="display:none;">
    <div id="score"></div>
    <div id="result-message"></div>
  </div>
</div>

<script>
const questions = [
  {q:"İlk buluşmamızda en çok nereye dikkat ettim?", options:[
    {text:"Gözlerine", score:3},
    {text:"Saçlarına", score:1},
    {text:"Gülüşüne", score:10},
    {text:"Kıyafetine", score:5},
  ]},
  {q:"En sevdiğim tatil türü hangisi?", options:[
    {text:"Deniz kenarı", score:10},
    {text:"Dağ yürüyüşü", score:3},
    {text:"Şehir turu", score:5},
    {text:"Evde dinlenmek", score:1},
  ]},
  {q:"En sevdiğim film türü nedir?", options:[
    {text:"Romantik komedi", score:10},
    {text:"Aksiyon", score:3},
    {text:"Korku", score:1},
    {text:"Belgesel", score:5},
  ]},
  {q:"Favori kahve tercihim nedir?", options:[
    {text:"Latte", score:5},
    {text:"Espresso", score:3},
    {text:"Americano", score:1},
    {text:"Türk kahvesi", score:10},
  ]},
  {q:"En sevdiğim mevsim hangisi?", options:[
    {text:"Yaz", score:5},
    {text:"Kış", score:3},
    {text:"Sonbahar", score:1},
    {text:"İlkbahar", score:10},
  ]},
  {q:"İlk tanıştığımızda aklımda kalan ilk şey?", options:[
    {text:"Gülüşün", score:10},
    {text:"Konuşman", score:5},
    {text:"Gözlerin", score:3},
    {text:"Kıyafetin", score:1},
  ]},
  {q:"En sevdiğim tatlı nedir?", options:[
    {text:"Çikolatalı kek", score:5},
    {text:"Dondurma", score:3},
    {text:"Baklava", score:1},
    {text:"Meyve", score:10},
  ]},
  {q:"En çok birlikte izlemeyi sevdiğimiz dizi türü?", options:[
    {text:"Romantik", score:10},
    {text:"Polisiye", score:3},
    {text:"Komedi", score:5},
    {text:"Belgesel", score:1},
  ]},
  {q:"En sevdiğim renk hangisi?", options:[
    {text:"Mor", score:5},
    {text:"Mavi", score:3},
    {text:"Kırmızı", score:1},
    {text:"Siyah", score:10},
  ]},
  {q:"Seninle en çok hangi ortamda vakit geçirmek isterim?", options:[
    {text:"Sessiz bir sahil", score:10},
    {text:"Kalabalık bir parti", score:1},
    {text:"Doğa yürüyüşü", score:5},
    {text:"Evde film gecesi", score:3},
  ]},
  {q:"En çok hangi şarkıyı seviyorum?", options:[
    {text:"Romantik ballad", score:10},
    {text:"Türk halk müziği", score:10},
    {text:"Pop", score:5},
    {text:"Rock", score:3},
  ]},
  {q:"En sevdiğim spor dalı nedir?", options:[
    {text:"Yürüyüş", score:10},
    {text:"Basketbol", score:1},
    {text:"Yoga", score:3},
    {text:"Futbol", score:5},
  ]},
  {q:"Beni en çok ne güldürür?", options:[
    {text:"Komik anılar", score:10},
    {text:"Şakalar", score:5},
    {text:"Film sahneleri", score:3},
    {text:"Sürprizler", score:1},
  ]},
  {q:"En sevdiğim çiçek nedir?", options:[
    {text:"Gül", score:10},
    {text:"Orkide", score:3},
    {text:"Papatya", score:5},
    {text:"Lale", score:1},
  ]},
  {q:"En çok hangi yemeği seviyorum?", options:[
    {text:"Makarna", score:5},
    {text:"Pizza", score:3},
    {text:"Salata", score:1},
    {text:"Kebap", score:10},
  ]},
  {q:"İlk kez “Seni seviyorum” dediğim anı nasıl hatırlarsın?", options:[
    {text:"Utangaç ve içten", score:10},
    {text:"Hızlı ve coşkulu", score:5},
    {text:"Sakin ve ciddi", score:3},
    {text:"Eğlenceli ve esprili", score:1},
  ]},
  {q:"En sevdiğim hayvan hangisi?", options:[
    {text:"Kedi", score:10},
    {text:"Köpek", score:5},
    {text:"Kuş", score:3},
    {text:"Balık", score:1},
  ]},
  {q:"Seninle en çok nerede vakit geçirmeyi seviyorum?", options:[
    {text:"Evimizde", score:10},
    {text:"Dışarıda", score:5},
    {text:"Sinemada", score:3},
    {text:"Parkta", score:1},
  ]},
  {q:"Hangi hediye beni en çok mutlu eder?", options:[
    {text:"El yapımı sürpriz", score:10},
    {text:"Takı", score:5},
    {text:"Kitap", score:3},
    {text:"Çiçek", score:1},
  ]},
  {q:"En çok hangi konuda bana güveniyorum?", options:[
    {text:"Duygularımı anlamanda", score:10},
    {text:"Gelecek planlarında", score:5},
    {text:"Günlük kararlarda", score:3},
    {text:"Küçük sırlarımda", score:1},
  ]},
  {q:"En sevdiğim meşhur film karakteri kimdir?", options:[
    {text:"Jack (Titanic)", score:5},
    {text:"Harry Potter", score:10},
    {text:"Forrest Gump", score:3},
    {text:"James Bond", score:1},
  ]},
  {q:"Hangi film türünü beraber izlemek isterim?", options:[
    {text:"Romantik drama", score:5},
    {text:"Bilim kurgu", score:3},
    {text:"Komedi", score:10},
    {text:"Korku", score:1},
  ]},
  {q:"Seninle yaşlanırken en çok neyi hayal ediyorum?", options:[
    {text:"El ele parkta yürümeyi", score:5},
    {text:"Evde huzur dolu günler", score:10},
    {text:"Seyahat etmeyi", score:3},
    {text:"Birlikte yemek yapmayı", score:1},
  ]}
];

let currentQuestionIndex = 0;
let totalScore = 0;

const questionEl = document.getElementById('question');
const optionsContainer = document.getElementById('options-container');
const nextBtn = document.getElementById('next-btn');
const scoreContainer = document.getElementById('score-container');
const scoreEl = document.getElementById('score');
const resultMessageEl = document.getElementById('result-message');

function showQuestion() {
  nextBtn.style.display = 'none';
  const currentQuestion = questions[currentQuestionIndex];
  questionEl.textContent = `${currentQuestionIndex + 1}. ${currentQuestion.q}`;
  optionsContainer.innerHTML = '';

  currentQuestion.options.forEach((option, index) => {
    const btn = document.createElement('button');
    btn.classList.add('option-btn');
    btn.textContent = option.text;
    btn.onclick = () => selectOption(option.score, btn);
    optionsContainer.appendChild(btn);
  });
}

function selectOption(score, btn) {
  totalScore += score;
  Array.from(optionsContainer.children).forEach(b => b.disabled = true);
  btn.style.backgroundColor = '#9d4edd';
  nextBtn.style.display = 'block';
}

nextBtn.addEventListener('click', () => {
  currentQuestionIndex++;
  if (currentQuestionIndex < questions.length) {
    showQuestion();
  } else {
    showScore();
  }
});

function showScore() {
  questionEl.style.display = 'none';
  optionsContainer.style.display = 'none';
  nextBtn.style.display = 'none';
  scoreContainer.style.display = 'block';
  scoreEl.textContent = `Toplam Puanın: ${totalScore}`;

  let message = '';
  if (totalScore >= 210) {
    message = 'Seni çok iyi tanıyorsun, aşkınız tam gaz devam ediyor!';
  } else if (totalScore >= 150) {
    message = 'Güzel gidiyorsun, biraz daha dikkatle harika olacaksınız!';
  } else {
    message = 'Biraz daha seni tanımaya çalış, aşk yolunda daha çok şey var!';
  }
  resultMessageEl.textContent = message;
}

// Başlat
showQuestion();
</script>

</body>
</html>
