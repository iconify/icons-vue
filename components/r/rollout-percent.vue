<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jmreqbcpp"/><path class="w5e91i9zv"/><path class="oohiueh8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rollout-percent" /></template>
<style>
.jmreqbcpp {
  d: path("M3.25 12a8.75 8.75 0 1 0 17.5 0a8.75 8.75 0 1 0-17.5 0Z");
}

.oohiueh8t {
  d: path("M9.75 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8 16.75c0-2.25 1.75-3.5 4-3.5s4 1.25 4 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5e91i9zv {
  fill: currentColor;
  d: path("M12 2a10 10 0 0 1 10 10h-2.5A7.5 7.5 0 0 0 12 4.5Z");
}

</style>
