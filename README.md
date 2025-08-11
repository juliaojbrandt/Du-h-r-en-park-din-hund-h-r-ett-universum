# Du-h-r-en-park-din-hund-h-r-ett-universum
<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Du hör en park – din hund hör ett universum</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background-image: url('Du hör en park din hund hör ett universum_Julia Öjbrandt.png'); /* byt till din bild */
      background-size: cover;
      background-position: center;
      position: relative;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
    }
    /* Mörk overlay */
    body::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.4);
      z-index: 0;
    }
    h1 {
      font-size: 1.8rem;
      z-index: 1;
      max-width: 80%;
      margin-bottom: 20px;
    }
    audio {
      width: 300px;
      z-index: 1;
    }
  </style>
</head>
<body>
  <h1>Du hör en park – din hund hör ett universum</h1>
  <audio controls>
    <source src="MITM - ljud park_test 1.mp3" type="audio/mpeg">
    Din webbläsare stödjer inte ljuduppspelning.
  </audio>
</body>
</html>
