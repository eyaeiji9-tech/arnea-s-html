# arnea-s-html
this is for educational purposes 
<link rel="stylesheet" href="style.css">
    <nav class="navbar">
      
    <h1>Story Book</h1>
    <div class="nav-links">
        <a href="#">Home</a>
        <a href="#">Stories</a>
        <a href="#">About</a>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero">
    <div class="hero-content">
        <h2>Step Into a World of Stories</h2>
        <p>Discover magical adventures, wonderful characters, and stories waiting to be explored.</p>
        <button>Explore Stories</button>
    </div>
</section>

<!-- About Section -->
<section class="about">
    <div class="about-image">
        <img src="https://tse2.mm.bing.net/th/id/OIP.fnVg8QDBdtUinZl8EV7cQQHaJQ?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="About our storybook">
    </div>
    <div class="about-content">
        <h2>About Our Storybook</h2>
        <p>Story Book is a collection of simple and inspiring stories created for readers who love imagination, adventure, and wonderful characters.</p>
    </div>
</section>

<!-- Stories Section -->
<section class="stories">
    <h2>Featured Stories</h2>
    <p class="section-description">Choose a story and discover a new world.</p>
    <div class="story-container">

        <!-- Story 1 -->
        <div class="story-card">
            <img src="https://img.wattpad.com/cover/31711753-256-k88188.jpg" alt="Romance Story">
            <h3>Possessive Series 1: Tyron Zapanta</h3>
            <p>Possessive Series 1: Tyron Zapanta by CeceLib is a romance story centered on Tyron Zapanta, a character whose intense feelings and possessive nature create a complicated relationship filled with attraction, jealousy, and emotional tension.</p>
            <button>Read More</button>
        </div>

        <!-- Story 2 -->
        <div class="story-card">
            <img src="https://img.wattpad.com/cover/32424576-200-k88203.jpg" alt="Romance Story">
            <h3>Possessive Series 2: Luhence Vergara</h3>
            <p>A romance story about Luhence Vergara, whose strong and possessive personality brings intense emotions and complicated relationships. The story explores love, jealousy, and passionate relationships.</p>
            <button>Read More</button>
        </div>

        <!-- Story 3 -->
        <div class="story-card">
            <img src="https://tse2.mm.bing.net/th/id/OIP.fnVg8QDBdtUinZl8EV7cQQHaJQ?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Romance, Mystery">
            <h3>Knock Knock, Professor</h3>
            <p>A romance story that follows the unexpected connection between a student and a professor. Filled with attraction, tension, and emotional complications, exploring love and boundaries.</p>
            <button>Read More</button>
        </div>

        <!-- Story 4 -->
        <div class="story-card">
            <img src="https://img.lazcdn.com/g/p/6e38a412b2363c12c5934b72e228b886.png_2200x2200q80.png_.webp" alt="Romance Story">
            <h3>The Rain España</h3>
            <p>The Rain by España is a romance story that follows two people whose lives become intertwined through unexpected circumstances. Filled with emotions, longing, and healing.</p>
            <button>Read More</button>
        </div>

        <!-- Story 5 -->
        <div class="story-card">
            <img src="https://tse1.explicit.bing.net/th/id/OIP.CnIKm0iknizyXXrGANUBIwHaLH?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" alt="Romance Story">
            <h3>Safe Skies, Archer</h3>
            <p>A romance story about Archer, who becomes an unexpected source of comfort and security. As their relationship develops, they face emotional challenges and the risks of falling in love.</p>
            <button>Read More</button>
        </div>

        <!-- Story 6 -->
        <div class="story-card">
            <img src="https://img.wattpad.com/cover/38201476-256-k88067.jpg" alt="Romance Story">
            <h3>Possessive Series 6: Dark Montero</h3>
            <p>Featuring a mysterious and intense male lead whose dark personality and complicated past make love anything but simple. Secrets, jealousy, and emotional conflicts challenge their relationship.</p>
            <button>Read More</button>
        </div>

    </div>
</section>


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f8f3e6;
  color: #333;
}

/* ===== NAVBAR ===== */
.navbar {
  background-color: #3f5139;
  padding: 12px 80px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navbar h1 {
  color: white;
}

.nav-links {
  display: flex;
  gap: 30px;
}

.nav-links a {
  color: white;
  text-decoration: none;
}

.nav-links a:hover {
  text-decoration: underline;
}

/* ===== HERO SECTION ===== */
.hero {
  min-height: 400px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #d9dfc8;
  padding: 40px 20px;
}

.hero-content {
  max-width: 700px;
}

.hero h2 {
  font-size: 45px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 18px;
  margin-bottom: 30px;
}

.hero button {
  padding: 12px 25px;
  border: none;
  border-radius: 5px;
  background-color: #3f5139;
  color: white;
  cursor: pointer;
}

.hero button:hover {
  background-color: #2f3f2b;
}

/* ===== ABOUT SECTION ===== */
.about {
  padding: 70px 60px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 50px;
  align-items: center;
}

.about-image img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}

.about-content h2 {
  font-size: 32px;
  margin-bottom: 20px;
  color: #3f5139;
}

.about-content p {
  line-height: 1.7;
  margin-bottom: 15px;
}

/* ===== STORIES SECTION ===== */
.stories {
  padding: 70px 60px;
  text-align: center;
}

.stories h2 {
  font-size: 35px;
  color: #3f5139;
}

.section-description {
  margin-top: 10px;
  margin-bottom: 40px;
}

/* STORY GRID */
.story-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 25px;
  text-align: left;
}

/* STORY CARD */
.story-card {
  background-color: white;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.story-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.story-card h3 {
  font-size: 21px;
  margin: 20px 20px 10px;
  color: #3f5139;
}

.story-card p {
  line-height: 1.5;
  margin: 0 20px 20px;
}

.story-card button {
  margin: 0 20px 20px;
  padding: 10px 18px;
  border: none;
  border-radius: 5px;
  background-color: #3f5139;
  color: white;
  cursor: pointer;
}

.story-card button:hover {
  background-color: #293721;
}


