---
title: Shunt Planner
---

# 🗺️ Shiny Hunt Route Planner

<div class="shunt-container">

  <div class="shunt-filters">
    <label for="region-select">Region</label>
    <select id="region-select">
      <option value="any">Any Region</option>
      <option value="kanto">Kanto</option>
      <option value="johto">Johto</option>
      <option value="hoenn">Hoenn</option>
      <option value="sinnoh">Sinnoh</option>
      <option value="unova">Unova</option>
    </select>
    <!-- -->
    <label for="target-select">Target Pokémon</label>
    <select id="target-select">
      <option value="">-- Choose a target --</option>
    </select>
    <!-- -->
    <label for="method-select">Hunt Method</label>
    <select id="method-select">
      <option value="any">Any</option>
      <option value="sweet-scent">Sweet Scent</option>
      <option value="repel-trick">Repel Trick</option>
      <option value="alpha">Alpha Swarms</option>
    </select>
  </div>

  <div class="shunt-results" id="results">
    <!-- Filtered data will appear here -->
  </div>

  <div class="shunt-controls">
    <h4>📌 Pinned Target</h4>
    <div id="pinned-target">None selected</div>
    <!-- -->
    <div class="shunt-sprites">
      <h4>✨ Sprites</h4>
      <div class="sprite-pair">
        <div>
          <div class="sprite-label">Normal</div>
          <img id="sprite-normal" src="" alt="Normal Sprite" />
        </div>
        <div>
          <div class="sprite-label">Shiny</div>
          <img id="sprite-shiny" src="" alt="Shiny Sprite" />
        </div>
      </div>
    </div>
    <!-- -->
    <h4>📝 Notes</h4>
    <textarea id="notes" rows="20" placeholder="Shunt Notes ..."></textarea>
    <button id="save-notes-btn">Save Notes</button>
    <button id="clear-notes-btn">Clear Notes</button>
  </div>

</div>

<script src="/many/assets/js/utilities/sp/shunt-planner.js"></script>
<link rel="stylesheet" href="/many/assets/css/utilities/shunt-planner.css">
