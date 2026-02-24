<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>關於《十七》</title>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: "Songti TC", "SimSun", serif;
    background: linear-gradient(135deg, #f8f6f2 0%, #f0eae2 100%);
    color: #222;
    line-height: 1.8;
    min-height: 100vh;
  }

  .back-home {
    position: fixed;
    top: 20px;
    left: 20px;
    width: 48px;
    height: 48px;
    cursor: pointer;
    z-index: 999;
    transition: transform 0.3s ease;
  }

  .back-home:hover {
    transform: scale(1.1);
  }

  .menu {
    position: fixed;
    top: 20px;
    right: 20px;
    display: flex;
    gap: 14px;
    background: rgba(255, 255, 255, 0.9);
    backdrop-filter: blur(10px);
    padding: 10px 14px;
    border-radius: 14px;
    box-shadow: 0 4px 20px rgba(0,0,0,0.08);
    z-index: 999;
  }

  .menu img {
    width: 48px;
    height: 48px;
    cursor: pointer;
    border-radius: 8px;
    transition: all 0.3s ease;
  }

  .menu img:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 12px rgba(0,0,0,0.1);
  }

  .container {
    max-width: 760px;
    margin: 0 auto;
    padding: 40px 20px;
  }

  .title {
    font-size: 36px;
    text-align: center;
    margin: 50px 0 30px;
    font-weight: normal;
    color: #1a1a1a;
    letter-spacing: 2px;
  }

  .cover {
    width: 60%;
    max-width: 400px;
    display: block;
    margin: 0 auto 40px;
    border-radius: 16px;
    box-shadow: 0 12px 30px rgba(0,0,0,0.15);
    transition: transform 0.3s ease;
  }

  .cover:hover {
    transform: scale(1.02);
  }

  .content {
    font-size: 18px;
    text-align: justify;
    margin-bottom: 30px;
    white-space: pre-line;
    background: rgba(255, 255, 255, 0.6);
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  }

  .section {
    display: none;
    animation: fadeIn 0.5s ease;
  }

  .section.active {
    display: block;
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .img-box {
    width: 80%;
    max-width: 500px;
    margin: 25px auto;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 6px 20px rgba(0,0,0,0.1);
  }

  .img-box img {
    width: 100%;
    display: block;
    transition: transform 0.3s ease;
  }

  .img-box img:hover {
    transform: scale(1.05);
  }

  audio {
    display: block;
    width: 100%;
    margin: 15px 0;
    background: rgba(255, 255, 255, 0.8);
    border-radius: 8px;
    padding: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }

  .section-title {
    font-size: 24px;
    margin: 40px 0 20px;
    text-align: center;
    color: #333;
    border-bottom: 1px solid rgba(0,0,0,0.1);
    padding-bottom: 10px;
  }
</style>
</head>
<body>

<img class="back-home" src="home.png" onclick="showPage('home')" title="回到關於《十七》">

<div class="menu">
  <img src="about_make.png" onclick="showPage('about-make')" title="關於製作">
  <img src="about_music.png" onclick="showPage('about-song')" title="關於曲">
  <img src="about_lyrics.png" onclick="showPage('about-lyric')" title="關於詞">
  <img src="about_mv.png" onclick="showPage('about-mv')" title="關於MV">
</div>

<div class="container">

  <!-- 首頁 -->
  <div class="section active" id="home">
    <h1 class="title">關於《十七》</h1>
    <img class="cover" src="mv-cover.JPG" alt="封面">
    <div class="content">
      點擊右上角圖示可閱讀製作相關內容。
    </div>
  </div>

  <!-- 關於製作 -->
  <div class="section" id="about-make">
    <h1 class="title">關於製作</h1>
    <div class="content">
      這裡可放製作整體介紹
    </div>
  </div>

  <!-- 關於曲 -->
  <div class="section" id="about-song">
    <h1 class="title">關於曲</h1>
    <div class="content">
wini：
這首歌並不是我寫的第一首歌，但是是第一首由自己在家錄製的歌，用著拼拼湊湊勉強能用的設備錄製，除了Guitar及Bass以外的樂器都是midi。
    </div>

    <div class="img-box">
      <img src="pic_music_1.jpg" alt="圖片1">
    </div>

    <div class="content">
說實話，「寫歌」本身這件事，並不困難，困難的是，在有期待的前提下，如何寫出來會令自己滿意。與我從前錄製guitar cover不同，即使彈錯，也不過是我已知並接受了的技術上的不足，但今次，這個logic file裡面每一條track都需要由我自己輸入，所以拍子上的偏差，是不容許存在的，因為一旦錯一條，全曲便會變得混亂。這首歌是團隊的，容不得在我這裡開始出錯。我開始埋怨自己，無論是技術上還是天賦上，也開始審視自己，自己是否有能力去完成與大家的承諾。好在，比起留在原地躊躇不前，我選擇了接受自己，把編曲控制在自己可以掌握的難度上。錄音當練習，幾個小節的片段可以錄上百次，比起錄音上的製作，編曲上，只要不如意便從頭來過，可謂任性，所以每個版本的demo都大相逕庭。
    </div>

    <div class="img-box">
      <img src="pic_music_2.jpg" alt="圖片2">
    </div>

    <div class="content">
最終版本敲定下來其實我是不滿意的，旋律普通不入耳、吉他太平淡、chord progression不夠豐富、琴聲太生硬、細節不夠、歌聲難聽刺耳、和聲太突兀等等。我總認為能做得更好，但是我現時能力貌似就到這裡了，時間上也不容許我繼續一改再改，青春總是會留上些遺憾的，我這樣安慰自己。
    </div>

    <div class="content">
我不是愛主動的人，但是製作總是要尋求意見的。雖然製作上有諸多不如意，但是在我開始主動的過程中我接收到了許多意料之外的溫暖，是同學試聽時表現的驚喜、是老師知曉後對製作進度的關心還有家裡人的鼓勵。這次歌曲裡用來錄製的bass甚至是和朋友借來的，謝謝你，還有謝謝幫我寫鼓的朋友。自己的製作能得到如此多回饋與幫助，我想自己簡直是世界上最幸福的人。

從f1開始學習的吉他與其餘自學的樂器注定了這次製作的粗糙，望大家嘴下留情。
    </div>

    <div class="section-title">Demo 試聽</div>
    <audio controls src="demo1.mp3">
    <audio controls src="demo2.mp3">
    <audio controls src="demo3.mp3">
  </div>

  <!-- 關於詞 -->
  <div class="section" id="about-lyric">
    <h1 class="title">關於詞</h1>
    <div class="content">等待你輸入內容…</div>
  </div>

  <!-- 關於MV -->
  <div class="section" id="about-mv">
    <h1 class="title">關於MV</h1>
    <div class="content">等待你輸入內容…</div>
  </div>

</div>

<script>
  function showPage(id) {
    document.querySelectorAll('.section').forEach(el => {
      el.classList.remove('active');
    });
    document.getElementById(id).classList.add('active');
  }
</script>
</body>
</html>
