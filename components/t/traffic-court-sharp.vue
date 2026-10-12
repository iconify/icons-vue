<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="odj2tvc3r"/><path class="j_rdrymqn"/><path class="axfc1_nyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:traffic-court-sharp" /></template>
<style>
.axfc1_nyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 15.25v6");
}

.j_rdrymqn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 5.75h.01M17 9h.01M17 12.25h.01");
}

.odj2tvc3r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.59 8.12l3.53-3.53l.71-.71l.71.71l.87.87l.71.71l-.71.71l-3.53 3.53l-.71.71l-.71-.71l-.87-.87l-.71-.71zm4.06.53L11 12m-8.25 6.75h9.5v2.5h-9.5zm11-16h6.5v12.5h-6.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
