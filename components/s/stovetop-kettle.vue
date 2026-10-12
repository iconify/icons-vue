<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cr_6_9b3y"/><path class="b4ct31bvf"/><circle class="tya1vzbon"/><path class="edjhu1bpr"/><path class="fyzvyrjwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stovetop-kettle" /></template>
<style>
.b4ct31bvf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 18.5h13a1.5 1.5 0 0 0 1.45-1.9c-1-3.6-3.95-6.35-7.95-6.35S5.05 13 4.05 16.6a1.5 1.5 0 0 0 1.45 1.9m12.25-4.75l2-2.75");
}

.cr_6_9b3y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 11.75c0-6 9.5-6 9.5 0");
}

.edjhu1bpr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 21.25h16.5");
}

.fyzvyrjwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.5h.01");
}

.tya1vzbon {
  cx: 20px;
  cy: 9.75px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
