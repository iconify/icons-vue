<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyvm7xbin"/><path class="lo7kp72nh"/><path class="ze3njkbee"/><path class="t47xolklb"/><path class="o9qd50bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swimming-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lo7kp72nh {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.o9qd50bgb {
  d: path("M2 18h3l3 -3 3 3 3 -3 3 3h5");
}

.t47xolklb {
  d: path("M9 11h8");
}

.yyvm7xbin {
  fill: currentColor;
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ze3njkbee {
  d: path("m9 10 4 -4");
}

</style>
