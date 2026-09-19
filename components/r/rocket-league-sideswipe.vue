<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="uollwjbzp"/><g class="y9tr6bcfx"><path class="fchoplpqz"/><path class="zbxcq42ko"/></g><circle class="a8h3yy45l"/><path class="ysh2racue"/><circle class="y4wy26fgj"/><path class="b124r1bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rocket-league-sideswipe" /></template>
<style>
.a8h3yy45l {
  cx: 20.675px;
  cy: 21.075px;
  r: 2.759px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.b124r1bpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.3 21.586c.834-.709 1.77-1.355 2.562-1.53c0 0-1.304-1.043-2.243-1.043c-.85-1.425-1.034-3.586-6.898-4.608c-4.35-.758-5.501.91-5.501.91l-5.851-.788l-1.03 1.334l.685.417l5.09 3.779m5.205 1.798l5.723 1.978m2.939-2.144c3.298-.478 6.254-.582 7.686 2.71m-6.599.821c.794 1.561 5.742 1.517 5.742 1.517");
}

.fchoplpqz {
  d: path("M11.914 30.23c3.871 6.601 8.172 9.893 12.55 12.763c2.293-1.503 4.564-3.125 6.764-5.272c-4.67-8.434-19.441-9.33-19.314-7.492");
}

.uollwjbzp {
  cx: 8.791px;
  cy: 10.161px;
  r: 5.154px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y4wy26fgj {
  cx: 31.294px;
  cy: 23.833px;
  r: 2.253px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ysh2racue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.023 16.277a2.534 2.534 0 0 0 4.06 3.015");
}

.zbxcq42ko {
  d: path("M6.805 14.918c.341 2.257.847 4.723 1.615 7.242c1.04 3.583 21.749 4.536 22.81 15.56c2.06-2.012 4.058-4.484 5.951-7.77c3.885-6.743 5.028-14.335 5.457-19.486c-4.79-2.425-10.333-4.039-18.174-4.032c-4.315-.003-7.934.484-11.115 1.326");
}

</style>
