<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jg1qo7ohz"/><path class="ee-_s3w4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-sharp-two-tone" /></template>
<style>
.ee-_s3w4p {
  d: path("M8 13L10 13C13.3137 13 16 15.6863 16 19L16 21L2 21L2 19C2 15.6863 4.6863 13 8 13ZM9 3C10.6569 3 12 4.3431 12 6C12 7.6569 10.6569 9 9 9C7.3431 9 6 7.6569 6 6C6 4.3431 7.3431 3 9 3ZM17.2496 2.3333L17.4853 3C17.8259 3.9635 18 4.978 18 6C18 7.022 17.8259 8.0365 17.4853 9L17.2496 9.6667M21.4667 2.2308L21.6491 3C21.8822 3.983 22 4.9898 22 6C22 8.282 21.3993 10.5238 20.2583 12.5L19.9697 13");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jg1qo7ohz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 12L10 12C13.7279 12 17 15.2721 17 19L17 21C17 21.5523 16.5523 22 16 22L2 22C1.4477 22 1 21.5523 1 21L1 19C1 15.2721 4.2721 12 8 12ZM9 2C11.0711 2 13 3.9289 13 6C13 8.0711 11.0711 10 9 10C6.9289 10 5 8.0711 5 6C5 3.9289 6.9289 2 9 2Z");
  stroke: none;
}

</style>
