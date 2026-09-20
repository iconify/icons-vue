<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hi2_i-t_x"/><path class="rcb4z6b_d"/><path class="t4v1u1jek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:planet-duotone-bold" /></template>
<style>
.hi2_i-t_x {
  fill: currentColor;
  d: path("M5 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rcb4z6b_d {
  d: path("M5 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4v1u1jek {
  d: path("M2 13c4 5 16 5 20 0");
}

</style>
