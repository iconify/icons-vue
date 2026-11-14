<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tshm4absc"/><path class="x819tbbba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toy-library" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tshm4absc {
  d: path("M2.5 21h19M5.25 4h2A1.75 1.75 0 0 1 9 5.75v13.5A1.75 1.75 0 0 1 7.25 21h-2a1.75 1.75 0 0 1-1.75-1.75V5.75A1.75 1.75 0 0 1 5.25 4M3.5 7.5H9m4.938 6.5h2.625a2.19 2.19 0 0 1 2.187 2.188v2.625A2.19 2.19 0 0 1 16.563 21h-2.625a2.19 2.19 0 0 1-2.188-2.187v-2.625A2.19 2.19 0 0 1 13.938 14");
}

.x819tbbba {
  d: path("M11.75 10.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
