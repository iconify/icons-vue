<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fs-evbclu"/><path class="h49lhzj_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-check-sharp-two-tone" /></template>
<style>
.fs-evbclu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 13L10 13C13.7279 13 17 16.2721 17 20L17 21C17 21.5523 16.5523 22 16 22L2 22C1.4477 22 1 21.5523 1 21L1 20C1 16.2721 4.2721 13 8 13ZM9 3C11.0711 3 13 4.9289 13 7C13 9.0711 11.0711 11 9 11C6.9289 11 5 9.0711 5 7C5 4.9289 6.9289 3 9 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h49lhzj_u {
  d: path("M8 14L10 14C13.3137 14 16 16.6863 16 20L16 21L2 21L2 20C2 16.6863 4.6863 14 8 14ZM9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3431 10 6 8.6569 6 7C6 5.3431 7.3431 4 9 4ZM15.7016 6.6644L18 9.25L22.2526 4.4659");
}

</style>
