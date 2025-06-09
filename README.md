<!DOCTYPE html>
<html lang="sw">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tovuti Yangu Nzuri</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }

    .hero {
      background-image: url('https://source.unsplash.com/1600x500/?nature,africa');
      background-size: cover;
      background-position: center;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
    }

    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .service {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }

    .service h3 {
      margin-bottom: 10px;
      color: #2c3e50;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    Karibu kwenye Tovuti Yetu
  </header>

  <section class="hero">
    Huduma Bora kwa Wateja wetu!
  </section>

  <div class="container">
    <h2 style="text-align:center; margin-bottom: 20px;">Huduma Zetu</h2>
    <div class="services">
      <div class="service">
        <h3>Huduma ya Mtandao</h3>
        <p>Tunatoa huduma bora ya kuunda tovuti na kusimamia mitandao yako ya kijamii.</p>
      </div>
      <div class="service">
        <h3>Ushauri wa Biashara</h3>
        <p>Tunakusaidia kukuza biashara yako kwa kutumia teknolojia na mbinu za kisasa.</p>
      </div>
      <div class="service">
        <h3>Mafunzo</h3>
        <p>Jifunze kuhusu teknolojia, programu na biashara kupitia kozi zetu mtandaoni.</p>
      </div>
    </div>
  </div>

  <footer>
    Mawasiliano: +255 123 456 789 | Email: info@tovutiyangu.com
  </footer>

</body>
</html>
