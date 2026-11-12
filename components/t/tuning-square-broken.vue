<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="vlfpssodi"/><circle class="cke3tihzk"/><path class="rzs0jlbll"/><path class="mg0h9nblz"/><path class="h1zzhq-sp"/><path class="eb7txqbka"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-square-broken" /></template>
<style>
.cke3tihzk {
  cx: 16px;
  cy: 14px;
  r: 2px;
}

.eb7txqbka {
  d: path("M16 19V18");
}

.h1zzhq-sp {
  d: path("M8 5V6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg0h9nblz {
  d: path("M16 10V5");
}

.rzs0jlbll {
  d: path("M8 14V19");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

.vlfpssodi {
  cx: 8px;
  cy: 10px;
  r: 2px;
}

</style>
