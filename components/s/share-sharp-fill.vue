<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t4vh4nb4c"/><path class="c8km_cwfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-sharp-fill" /></template>
<style>
.c8km_cwfm {
  fill: currentColor;
  d: path("M22 5C22 7.0711 20.0711 9 18 9C15.9289 9 14 7.0711 14 5C14 2.9289 15.9289 1 18 1C20.0711 1 22 2.9289 22 5ZM10 12C10 14.0711 8.0711 16 6 16C3.9289 16 2 14.0711 2 12C2 9.9289 3.9289 8 6 8C8.0711 8 10 9.9289 10 12ZM22 19C22 21.0711 20.0711 23 18 23C15.9289 23 14 21.0711 14 19C14 16.9289 15.9289 15 18 15C20.0711 15 22 16.9289 22 19Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t4vh4nb4c {
  d: path("M8.5913 10.4884L15.4087 6.5116M8.5913 13.5116L15.4087 17.4884");
}

</style>
