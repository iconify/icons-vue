<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e1sjf3sod"/><path class="thhb-lizz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rotate-anticlockwise-2-line-duotone" /></template>
<style>
.e1sjf3sod {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 7.4286V4H19.75M16 4C19.125 6.8571 21 9 21 12C21 15 19.2476 18.2857 16 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.thhb-lizz {
  d: path("M10.9289 14.9289C12.3096 13.5482 13 12.8579 13 12C13 11.1421 12.3096 10.4518 10.9289 9.0711C9.5482 7.6904 8.8579 7 8 7C7.1421 7 6.4518 7.6904 5.0711 9.0711C3.6904 10.4518 3 11.1421 3 12C3 12.8579 3.6904 13.5482 5.0711 14.9289C6.4518 16.3096 7.1421 17 8 17C8.8579 17 9.5482 16.3096 10.9289 14.9289Z");
}

</style>
