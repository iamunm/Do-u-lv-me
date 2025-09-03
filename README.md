<video class="local-gif" src="reply-me-love.mp4" autoplay muted playsinline loop></video>
...
<video class="gif-result" src="love-me.mp4" autoplay muted playsinline loop></video>
// before gifResult.play();
gifResult.muted = false;
gifResult.currentTime = 0;
gifResult.play();
