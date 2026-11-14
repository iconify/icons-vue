<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i8m6meefs"/><path class="x0a1ufw4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-bearded" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8m6meefs {
  d: path("M7.75 7.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

.x0a1ufw4y {
  d: path("M7.75 8c0 5 2.25 8 4.25 8.5c2-.5 4.25-3.5 4.25-8.5M3.5 21.5c0-2.5 1.75-3.75 4.5-4m8 0c2.75.25 4.5 1.5 4.5 4");
}

</style>
