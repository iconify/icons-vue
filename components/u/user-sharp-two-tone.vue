<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i8hq46b4m"/><path class="j4wwmxbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i8hq46b4m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 13L13 13C16.7279 13 20 16.2721 20 20L20 21C20 21.5523 19.5523 22 19 22L5 22C4.4477 22 4 21.5523 4 21L4 20C4 16.2721 7.2721 13 11 13ZM12 3C14.0711 3 16 4.9289 16 7C16 9.0711 14.0711 11 12 11C9.9289 11 8 9.0711 8 7C8 4.9289 9.9289 3 12 3Z");
  stroke: none;
}

.j4wwmxbht {
  d: path("M11 14L13 14C16.3137 14 19 16.6863 19 20L19 21L5 21L5 20C5 16.6863 7.6863 14 11 14ZM12 4C13.6569 4 15 5.3431 15 7C15 8.6569 13.6569 10 12 10C10.3431 10 9 8.6569 9 7C9 5.3431 10.3431 4 12 4Z");
}

</style>
