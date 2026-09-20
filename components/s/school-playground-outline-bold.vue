<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k4qo1xe9v"/><path class="rjl8fe1sw"/><path class="ed-cudrmv"/><path class="i7797vbcv"/><path class="gzw9grb_d"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:school-playground-outline-bold" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.ed-cudrmv {
  d: path("M20 6v14");
}

.gzw9grb_d {
  d: path("M15 6v9");
}

.i7797vbcv {
  d: path("M9 6v9");
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.rjl8fe1sw {
  d: path("M4 6v14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
