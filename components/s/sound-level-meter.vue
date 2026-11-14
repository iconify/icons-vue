<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g30sj5bid"/><path class="vy7hrfsgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sound-level-meter" /></template>
<style>
.g30sj5bid {
  d: path("M4 4.5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2V13l-2 8.5H6L4 13Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vy7hrfsgo {
  d: path("M6.25 8.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m10.225-2.475a3.5 3.5 0 0 1 0 4.95m2.887-6.975a7 7 0 0 1 0 9");
}

</style>
