<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lxnzn9nmw"/><circle class="vlfpssodi"/><circle class="cke3tihzk"/><path class="rzs0jlbll"/><path class="mg0h9nblz"/><path class="h1zzhq-sp"/><path class="eb7txqbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-square-line-duotone" /></template>
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

.lxnzn9nmw {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mg0h9nblz {
  d: path("M16 10V5");
}

.rzs0jlbll {
  d: path("M8 14V19");
}

.vlfpssodi {
  cx: 8px;
  cy: 10px;
  r: 2px;
}

</style>
