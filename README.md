# joel641.github.io
<h1>👋 Hello you are here</h1>

<div id="embedContainer" style="position: relative; width: 100%; height: 600px;">
  <iframe 
    id="embedFrame"
    src="https://www.easyfun.gg/cloud-games/roblox.html" 
    width="100%" 
    height="100%" 
    style="border: none;" 
    allowfullscreen
    allow="fullscreen">
  </iframe>
  <button id="fullscreenBtn" style="position: absolute; top: 10px; right: 10px; z-index: 999; padding: 8px 12px; background: rgba(0,0,0,0.5); color: #fff; border: none; cursor: pointer;">
    Fullscreen
  </button>
</div>

<script>
  document.getElementById('fullscreenBtn').addEventListener('click', function() {
    var container = document.getElementById('embedContainer');
    if (container.requestFullscreen) {
      container.requestFullscreen();
    } else if (container.mozRequestFullScreen) { // Firefox
      container.mozRequestFullScreen();
    } else if (container.webkitRequestFullscreen) { // Chrome, Safari and Opera
      container.webkitRequestFullscreen();
    } else if (container.msRequestFullscreen) { // IE/Edge
      container.msRequestFullscreen();
    }
  });
</script>
