<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gu4_cx-8v"/><path class="fyvf420mr"/><path class="n04sz6gmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rice-duotone-thin" /></template>
<style>
.fyvf420mr {
  d: path("M4 11h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

.gu4_cx-8v {
  fill: currentColor;
  d: path("M4 11h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n04sz6gmp {
  d: path("M7 11a5 5 0 0 1 10 0");
}

</style>
