<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wtaa8jpxo"/><path class="ccdryp6-a"/><path clip-rule="evenodd" class="btwd0w9_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-alert-sharp-two-tone" /></template>
<style>
.btwd0w9_q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 9C20 9.5523 19.5523 10 19 10C18.4477 10 18 9.5523 18 9C18 8.4477 18.4477 8 19 8C19.5523 8 20 8.4477 20 9Z");
  stroke: none;
}

.ccdryp6-a {
  d: path("M11 13L13 13C16.3137 13 19 15.6863 19 19L19 21L5 21L5 19C5 15.6863 7.6863 13 11 13ZM12 3C13.6569 3 15 4.3431 15 6C15 7.6569 13.6569 9 12 9C10.3431 9 9 7.6569 9 6C9 4.3431 10.3431 3 12 3ZM19 2L19 6");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wtaa8jpxo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 12L13 12C16.7279 12 20 15.2721 20 19L20 21C20 21.5523 19.5523 22 19 22L5 22C4.4477 22 4 21.5523 4 21L4 19C4 15.2721 7.2721 12 11 12ZM12 2C14.0711 2 16 3.9289 16 6C16 8.0711 14.0711 10 12 10C9.9289 10 8 8.0711 8 6C8 3.9289 9.9289 2 12 2Z");
  stroke: none;
}

</style>
