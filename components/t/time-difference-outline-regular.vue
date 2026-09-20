<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h51gqww2n"/><path class="wquo_ibsk"/><path class="f8n4gobtp"/><path class="mc3x0bbgo"/><path class="w9rzo5b1c"/><path class="lgk47ib7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:time-difference-outline-regular" /></template>
<style>
.f8n4gobtp {
  d: path("M6.5 12h3");
}

.h51gqww2n {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.lgk47ib7d {
  d: path("M14.5 12h3");
}

.mc3x0bbgo {
  d: path("M13 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w9rzo5b1c {
  d: path("M17.5 12v3.5");
}

.wquo_ibsk {
  d: path("M6.5 8.5V12");
}

</style>
