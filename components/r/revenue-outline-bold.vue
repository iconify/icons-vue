<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o610cu0jy"/><path class="u_pwg_bmr"/><path class="lev20-kjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:revenue-outline-bold" /></template>
<style>
.lev20-kjj {
  d: path("m14 17 2.5 -2.5 2 2L22 13");
}

.o610cu0jy {
  d: path("M2.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u_pwg_bmr {
  d: path("M7 10.5v3");
}

</style>
