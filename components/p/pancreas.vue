<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2h2rng0h"/><path class="rho0cyy6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pancreas" /></template>
<style>
.a2h2rng0h {
  d: path("M3.25 14.5c0-2 1.5-3.75 3.5-3.75c1.5 0 2.5-1 4-2.25c1.75-1.5 3.75-2.25 6-2s4 1.5 4 3.5c0 1.75-1.5 2.75-3.25 3c-2 .25-3.75.75-5.25 2c-1.25 1-1.5 3-3.25 3.75c-1 .5-2.25.5-3.25.25c-1.5-.5-2.5-2.5-2.5-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rho0cyy6f {
  d: path("M6 15c2.25 0 3.75-2.25 6.25-3.5c2-1 4.25-1.5 6.25-1.5");
}

</style>
