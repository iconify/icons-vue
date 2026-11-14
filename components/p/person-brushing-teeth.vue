<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggpzoebve"/><path class="pnakcdffx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-brushing-teeth" /></template>
<style>
.ggpzoebve {
  d: path("M6.5 21.5V18C4.25 16.5 3 14 3 11.25C3 7 6 4 10 4c3.25 0 5.5 2.25 5.5 5.5l1.25 2.5c.25.5-.1.75-.75.75h-.5V17c0 .85-.65 1.5-1.5 1.5h-1.5v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pnakcdffx {
  d: path("m17.241 14.943l3.277 2.294a1.25 1.25 0 0 1 .306 1.741a1.25 1.25 0 0 1-1.74.307l-3.277-2.294a1.25 1.25 0 0 1-.307-1.741a1.25 1.25 0 0 1 1.741-.307");
}

</style>
