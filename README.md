<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Khel Ghar – Free Online Games</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="header">
    <h1 class="logo">🎮 Khel Ghar</h1>
    <p class="tagline">Free Online Games – Mobile Friendly</p>
  </header>

  <main class="main">
    <div class="search-box">
      <input type="text" id="searchInput" placeholder="Search games..." autocomplete="off">
    </div>

    <div class="filters" id="filters">
      <button class="filter-btn active" data-category="All">All</button>
    </div>

    <div class="games-grid" id="gamesGrid"></div>

    <div class="load-more-wrap">
      <button id="loadMoreBtn" class="load-more-btn">Load More</button>
    </div>

    <p id="noResults" class="no-results" hidden>No games found.</p>
  </main>

  <footer class="footer">
    <p>© 2026 Khel Ghar · All games are free & open-source</p>
  </footer>

  <div id="gameModal" class="modal" hidden>
    <div class="modal-content">
      <div class="modal-header">
        <h2 id="modalTitle"></h2>
        <button id="closeModal" class="close-btn">✕</button>
      </div>
      <iframe id="gameFrame" src="" sandbox="allow-scripts allow-same-origin allow-pointer-lock" allowfullscreen></iframe>
      <div class="modal-footer">
        <small id="modalSource"></small>
      </div>
    </div>
  </div>

  <script src="app.js"></script>
</body>
</html>
