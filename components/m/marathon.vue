<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="lv66fte6s"/><path class="c4oqnknem"/><path class="f1hzpac_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:marathon" /></template>
<style>
.c4oqnknem {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 6.75h.01m10.49 0h.01");
}

.f1hzpac_e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17v-6.5L6.5 15h4m3-2.5a2 2 0 0 1 4 0c0 1.75-1.5 2.5-4 4.5h4.25");
}

.lv66fte6s {
  width: 17.5px;
  height: 16.5px;
  x: 3.25px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
