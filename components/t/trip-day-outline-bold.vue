<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d3xn50bni"/><path class="j9d013d3m"/><path class="r6n4eub3d"/><path class="bwqs5tbzt"/><path class="gf918zbnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trip-day-outline-bold" /></template>
<style>
.bwqs5tbzt {
  d: path("M11.5 13a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.gf918zbnb {
  d: path("M11 18h7");
}

.j9d013d3m {
  d: path("M9 2v20");
}

.r6n4eub3d {
  d: path("M11 7h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
