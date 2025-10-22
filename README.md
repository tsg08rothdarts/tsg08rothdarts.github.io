<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TSG 08 Roth – 2K Dart Suche</title>
  <script>
    window.onload = function() {
      // Zielseite öffnen
      window.location.href = "https://2k-dart-software.com/frontend/events";
      // Versuch, Suchfeld auszufüllen (für Browser, die Skripte weitergeben)
      setTimeout(() => {
        try {
          const input = document.querySelector('input[type="app-search-box"], input[placeholder*="Suche"]');
          if (input) {
            input.value = "TSG 08 Roth";
            input.dispatchEvent(new Event("input", { bubbles: true }));
          }
        } catch (e) { /* ignorieren */ }
      }, 3000);
    };
  </script>
</head>
<body>
  <p>Weiterleitung zur 2K-Dart-Software …</p>
</body>
</html>
