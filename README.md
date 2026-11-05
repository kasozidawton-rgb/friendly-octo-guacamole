# friendly-octo-guacamole
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GREEN EARTH | Environmental Pollution</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #f0f7f1;
  color: #203b2a;
}

header {
  background: #063d27;
  color: white;
  padding: 20px 7%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

.logo {
  font-size: 25px;
  font-weight: bold;
  color: #a5e6a9;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 10px;
  font-weight: bold;
}

nav a:hover {
  color: #a5e6a9;
}

.hero {
  min-height: 550px;
  background:
  linear-gradient(rgba(0,30,15,.65),
  rgba(0,30,15,.65)),
  url("https://images.unsplash.com/photo-1448375240586-882707db888b?w=1800")
  center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
  padding: 40px 20px;
}

.hero h1 {
  font-size: clamp(38px, 7vw, 65px);
  margin-bottom: 20px;
  color: #a9f0a9;
}

.hero p {
  font-size: 20px;
  max-width: 750px;
  line-height: 1.7;
  margin: auto;
}

.btn {
  display: inline-block;
  margin-top: 25px;
  background: #42a85b;
  color: white;
  padding: 15px 28px;
  text-decoration: none;
  border-radius: 30px;
  font-weight: bold;
}

section {
  padding: 75px 8%;
  text-align: center;
}

h2 {
  font-size: 35px;
  color: #126038;
  margin-bottom: 20px;
}

.intro {
  max-width: 850px;
  margin: auto;
  line-height: 1.8;
  font-size: 18px;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(230px,1fr));
  gap: 25px;
  margin-top: 35px;
}

.card {
  background: white;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 5px 18px #0002;
  transition: .3s;
  text-align: left;
}

.card:hover {
  transform: translateY(-8px);
}

.card img {
  width: 100%;
  height: 190px;
  object-fit: cover;
}

.card-content {
  padding: 22px;
}

.card h3 {
  color: #14713b;
  margin-bottom: 12px;
}

.card p {
  line-height: 1.6;
}

.dark {
  background: #063d27;
  color: white;
}

.dark h2 {
  color: #a9e9a9;
}

.team {
  background: white;
  padding: 35px;
  max-width: 750px;
  margin: 30px auto;
  border-radius: 18px;
  box-shadow: 0 5px 20px #0002;
}

.team ul {
  list-style: none;
  text-align: left;
}

.team li {
  padding: 14px;
  margin: 8px 0;
  background: #edf7ed;
  border-left: 5px solid #23964e;
  border-radius: 5px;
  font-weight: bold;
}

footer {
  background: #032b1c;
  color: white;
  text-align: center;
  padding: 30px;
  line-height: 2;
}

.top {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #168443;
  color: white;
  padding: 14px;
  border-radius: 50%;
  text-decoration: none;
}

@media(max-width:650px) {
  header {
    justify-content: center;
    gap: 15px;
  }
  nav {
    text-align: center;
  }
  nav a {
    display: inline-block;
    font-size: 13px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">🌍 GREEN EARTH</div>
  <nav>
    <a href="#home">HOME</a>
    <a href="#about">ABOUT</a>
    <a href="#types">TYPES</a>
    <a href="#effects">EFFECTS</a>
    <a href="#solutions">SOLUTIONS</a>
    <a href="#team">TEAM</a>
  </nav>
</header>

<div class="hero" id="home">
  <div>
    <h1>SAVE OUR PLANET</h1>
    <p>
      Environmental pollution is a serious threat
      to life on Earth. Together, we can protect
      nature and create a cleaner, greener future.
    </p>
    <a class="btn" href="#about">EXPLORE PROJECT</a>
  </div>
</div>

<section id="about">
  <h2>ABOUT ENVIRONMENTAL POLLUTION</h2>
  <p class="intro">
    Environmental pollution is the introduction of
    harmful substances into our surroundings.
    It affects air, water and land, causing harm
    to humans, animals, plants and the environment.
    Pollution is caused by human activities such as
    industrial waste, deforestation, poor waste
    disposal and vehicle emissions.
  </p>
</section>

<section id="types" style="background:#e1f0e3">
  <h2>TYPES OF POLLUTION</h2>
  <p class="intro">
    There are different forms of environmental pollution.
    The following are some of the major types.
  </p>

  <div class="cards">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1516937941344-00b4e0337589?w=800" alt="Factory smoke">
      <div class="card-content">
        <h3>AIR POLLUTION</h3>
        <p>Air pollution happens when smoke, dust and harmful gases enter the atmosphere and make the air unsafe to breathe.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1439405326854-014607f694d7?w=800" alt="Water">
      <div class="card-content">
        <h3>WATER POLLUTION</h3>
        <p>Water pollution occurs when chemicals, sewage and rubbish contaminate rivers, lakes and oceans.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1532996122724-e3c354a0b15b?w=800" alt="Plastic waste">
      <div class="card-content">
        <h3>LAND POLLUTION</h3>
        <p>Land pollution results from dumping rubbish, plastics and harmful chemicals onto the ground.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1473448912268-2022ce9509d8?w=800" alt="Forest">
      <div class="card-content">
        <h3>NOISE POLLUTION</h3>
        <p>Noise pollution is excessive or disturbing sound from vehicles, factories, machines and loud music.</p>
      </div>
    </div>
  </div>
</section>

<section id="effects">
  <h2>EFFECTS OF POLLUTION</h2>
  <div class="cards">
    <div class="card">
      <div class="card-content">
        <h3>🫁 Human Health</h3>
        <p>Pollution can cause breathing problems, diseases and other health complications.</p>
      </div>
    </div>
    <div class="card">
      <div class="card-content">
        <h3>🐟 Aquatic Life</h3>
        <p>Dirty water harms fish and other organisms living in rivers, lakes and oceans.</p>
      </div>
    </div>
    <div class="card">
      <div class="card-content">
        <h3>🌳 Climate Change</h3>
        <p>Some forms of pollution release greenhouse gases that contribute to global warming.</p>
      </div>
    </div>
    <div class="card">
      <div class="card-content">
        <h3>🌱 Soil Damage</h3>
        <p>Pollution can reduce soil quality and affect agricultural production.</p>
      </div>
    </div>
  </div>
</section>

<section class="dark" id="solutions">
  <h2>HOW CAN WE STOP POLLUTION?</h2>
  <div class="cards">
    <div class="card">
      <div class="card-content">
        <h3>🌳 Plant Trees</h3>
        <p>Plant and protect trees to improve the environment.</p>
      </div>
    </div>
    <div class="card">
      <div class="card-content">
        <h3>♻️ Recycle Waste</h3>
        <p>Reuse and recycle materials instead of throwing them away.</p>
      </div>
    </div>
    <div class="card">
      <div class="card-content">
        <h3>🚯 Proper Disposal</h3>
        <p>Dispose of rubbish in appropriate waste bins.</p>
      </div>
    </div>
    <div class="card">
      <div class="card-content">
        <h3>💧 Protect Water</h3>
        <p>Avoid dumping chemicals and waste into water bodies.</p>
      </div>
    </div>
  </div>
</section>

<section id="team">
  <h2>OUR PROJECT TEAM</h2>
  <p class="intro">
    This project was prepared through teamwork
    and cooperation by the following members.
  </p>

  <div class="team">
    <h2 style="color: #601b12; text-align: center;">A PRODUCT FROM S.1 STUDENTS OF S.1 ONE CENTRAL AT MENGO S.S</h2>
    <ul>
      <li>01. KASOZI DAWTON</li>
      <li>02. HUSSEIN GERE</li>
      <li>03. LUTAAYA MARTIN — CHAIRPERSON</li>
      <li>04. LUTAYA AURTHER</li>
      <li>05. MURUNJI JOSEPHINE — SUPERVISOR</li>
      <li>06. WAISUKIRAWA GOODLUCK</li>
      <li>07. AGABA CALTON</li>
      <li>08. MUHINDO ROHI</li>
      <li>09.LULE  JEREMIAH</li>
    </ul>
  </div>
</section>

<section style="background:#dceede">
  <h2>OUR MESSAGE TO THE WORLD</h2>
  <p class="intro">
    "The Earth is our home. Protecting it is
    everyone's responsibility. Let us reduce
    pollution, keep our environment clean and
    make the world a better place for future
    generations."
  </p>
  <h2 style="margin-top:25px">GO GREEN, KEEP IT CLEAN! 🌍</h2>
</section>

<footer>
  <h3>🌍 GREEN EARTH PROJECT</h3>
  <p>Environmental Pollution Awareness Project</p>
  <p>Prepared by our project team of  MENGO SS S1 central</p>
  <p>© 2026 GREEN EARTH. Protect Our Planet.</p>
</footer>

<a href="#home" class="top">↑</a>

<script>
  // Smooth navigation and welcome message
  window.addEventListener("load", function() {
    console.log("Welcome to GREEN EARTH!");
  });
</script>

</body>
</html>
