# Landing-page-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Claim Your Free Gift Card Now!</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@600&family=Roboto&display=swap');

  body {
    margin: 0; padding: 0;
    font-family: 'Roboto', sans-serif;
    background: linear-gradient(135deg, #ff7e5f, #feb47b);
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    text-align: center;
    overflow-x: hidden;
  }
  .container {
    background: rgba(255, 255, 255, 0.1);
    padding: 50px 30px;
    border-radius: 30px;
    box-shadow: 0 8px 40px rgba(255, 126, 95, 0.6);
    max-width: 480px;
    width: 90%;
  }
  h1 {
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
    font-size: 3rem;
    margin-bottom: 15px;
    text-shadow: 0 4px 10px rgba(0,0,0,0.2);
  }
  p.subheading {
    font-size: 1.25rem;
    margin-bottom: 40px;
    text-shadow: 0 2px 8px rgba(0,0,0,0.15);
    color: #ffe8d6;
  }
  .gift-card-img {
    max-width: 100%;
    border-radius: 25px;
    box-shadow: 0 8px 30px rgba(0,0,0,0.3);
    margin-bottom: 50px;
    transition: transform 0.3s ease;
  }
  .gift-card-img:hover {
    transform: scale(1.05) rotate(3deg);
  }
  .btn-gift {
    background: linear-gradient(45deg, #ff416c, #ff4b2b);
    border: none;
    padding: 20px 70px;
    font-size: 1.6rem;
    font-weight: 700;
    color: #fff;
    border-radius: 50px;
    cursor: pointer;
    box-shadow: 0 6px 25px rgba(255,75,43,0.7);
    transition: all 0.3s ease;
    animation: glowPulse 3s infinite alternate;
  }
  .btn-gift:hover {
    background: linear-gradient(45deg, #ff4b2b, #ff416c);
    box-shadow: 0 0 40px #ff4b2b, 0 0 80px #ff416c;
    transform: scale(1.1);
  }

  @keyframes glowPulse {
    0% {
      box-shadow: 0 0 10px #ff4b2b, 0 0 20px #ff416c;
    }
    100% {
      box-shadow: 0 0 30px #ff4b2b, 0 0 60px #ff416c;
    }
  }

  /* Responsive */
  @media (max-width: 600px) {
    h1 {
      font-size: 2.2rem;
    }
    p.subheading {
      font-size: 1.1rem;
    }
    .btn-gift {
      padding: 16px 50px;
      font-size: 1.3rem;
    }
  }
</style>
</head>
<body>

<div class="container">
  <h1>Unlock Your FREE Gift Card Now!</h1>
  <p class="subheading">Limited time offer — Don’t miss out on exciting rewards. Click below to claim your gift instantly!</p>
  
  <img class="gift-card-img" src="https://images.unsplash.com/photo-1567016572849-7b40f4b18f46?auto=format&fit=crop&w=800&q=80" alt="Gift Card" />
  
  <button class="btn-gift" onclick="window.location.href='https://your-offer-link.com'">Claim Gift Card</button>
</div>

</body>
</html>
