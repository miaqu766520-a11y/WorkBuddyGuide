<template>
  <svg
    class="wb-pixel-icon-sprite"
    aria-hidden="true"
    focusable="false"
  >
    <defs>
      <!-- 杂志编辑风：细线插画图标（stroke 风格，24×24 网格） -->
      <symbol id="wb-pixel-arrow-right" viewBox="0 0 24 24">
        <path d="M4 12h15" />
        <path d="M13 5l7 7-7 7" />
      </symbol>
      <symbol id="wb-pixel-book" viewBox="0 0 24 24">
        <path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20" />
        <path d="M4 19.5A2.5 2.5 0 0 0 6.5 22H20V2H6.5A2.5 2.5 0 0 0 4 4.5v15z" />
      </symbol>
      <symbol id="wb-pixel-briefcase" viewBox="0 0 24 24">
        <rect x="2.5" y="7" width="19" height="13" rx="2" />
        <path d="M8.5 7V5a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v2" />
      </symbol>
      <symbol id="wb-pixel-chart-line" viewBox="0 0 24 24">
        <path d="M3 3v16a2 2 0 0 0 2 2h16" />
        <path d="M7 14l4-4 3 3 5-6" />
      </symbol>
      <symbol id="wb-pixel-check-box" viewBox="0 0 24 24">
        <path d="M9 11.5l2.5 2.5L20 5.5" />
        <path d="M20 12v6a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h9" />
      </symbol>
      <symbol id="wb-pixel-face-grin" viewBox="0 0 24 24">
        <circle cx="12" cy="12" r="9" />
        <path d="M8.5 14c1 1.5 2.2 2 3.5 2s2.5-.5 3.5-2" />
        <path d="M9 9.5v1.5" />
        <path d="M15 9.5v1.5" />
      </symbol>
      <symbol id="wb-pixel-folder-open" viewBox="0 0 24 24">
        <path d="M3 6a2 2 0 0 1 2-2h4l2 3h8a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z" />
        <path d="M3 11h18" />
      </symbol>
      <symbol id="wb-pixel-grid" viewBox="0 0 24 24">
        <rect x="3.5" y="3.5" width="7" height="7" rx="1" />
        <rect x="13.5" y="3.5" width="7" height="7" rx="1" />
        <rect x="3.5" y="13.5" width="7" height="7" rx="1" />
        <rect x="13.5" y="13.5" width="7" height="7" rx="1" />
      </symbol>
      <symbol id="wb-pixel-handshake" viewBox="0 0 24 24">
        <path d="m11 17 2 2a1 1 0 1 0 3-3" />
        <path d="m14 14 2.5 2.5a1 1 0 1 0 3-3l-3.88-3.88a3 3 0 0 0-4.24 0l-.88.88a1 1 0 1 1-3-3l2.81-2.81a5.79 5.79 0 0 1 7.06-.87l.47.28a2 2 0 0 0 1.42.25L21 4" />
        <path d="m21 3 1 11h-2" />
        <path d="M3 3 2 14l6.5 6.5a1 1 0 1 0 3-3" />
        <path d="M3 4h8" />
      </symbol>
      <symbol id="wb-pixel-newspaper" viewBox="0 0 24 24">
        <rect x="4" y="4" width="16" height="16" rx="1.5" />
        <path d="M7.5 8h5v4h-5z" />
        <path d="M15 8.5h2" />
        <path d="M15 11.5h2" />
        <path d="M7.5 15.5h9" />
      </symbol>
      <symbol id="wb-pixel-refresh" viewBox="0 0 24 24">
        <path d="M23 4v6h-6" />
        <path d="M1 20v-6h6" />
        <path d="M3.51 9a9 9 0 0 1 14.85-3.36L23 10" />
        <path d="M1 14l4.64 4.36A9 9 0 0 0 20.49 15" />
      </symbol>
      <symbol id="wb-pixel-robot" viewBox="0 0 24 24">
        <rect x="4" y="8" width="16" height="11" rx="2" />
        <path d="M12 8V4.5" />
        <circle cx="12" cy="3.5" r="1" />
        <path d="M9 12.5v2" />
        <path d="M15 12.5v2" />
        <path d="M2 12.5v3" />
        <path d="M22 12.5v3" />
      </symbol>
      <symbol id="wb-pixel-sitemap" viewBox="0 0 24 24">
        <rect x="9" y="3" width="6" height="5" rx="1" />
        <rect x="3" y="16" width="6" height="5" rx="1" />
        <rect x="15" y="16" width="6" height="5" rx="1" />
        <path d="M12 8v5" />
        <path d="M6 16v-2a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v2" />
      </symbol>
      <symbol id="wb-pixel-user" viewBox="0 0 24 24">
        <circle cx="12" cy="7" r="4" />
        <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2" />
      </symbol>
      <symbol id="wb-pixel-users" viewBox="0 0 24 24">
        <circle cx="9.5" cy="7" r="4" />
        <path d="M2 21v-2a4 4 0 0 1 4-4h7a4 4 0 0 1 4 4v2" />
        <path d="M22 21v-2a4 4 0 0 0-3-3.87" />
        <path d="M15.5 3.13a4 4 0 0 1 0 7.75" />
      </symbol>
      <symbol id="wb-pixel-video-camera" viewBox="0 0 24 24">
        <rect x="1" y="5" width="15" height="14" rx="2" />
        <path d="M23 7l-7 5 7 5V7z" />
      </symbol>
    </defs>
  </svg>
</template>
