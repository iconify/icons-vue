<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xkhvjmrzg"/><path class="mbkrrbmod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:zinnia" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbkrrbmod {
  d: path("M9.75 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m2.25 11c1.5-2 4-2.5 6.5-2c-1.5 2-4 2.75-6.5 2");
}

.xkhvjmrzg {
  d: path("M17.75 9.5a2.25 2.25 0 0 1-1.75 4a2.25 2.25 0 0 1-4 1.75a2.25 2.25 0 0 1-4-1.75a2.25 2.25 0 0 1-1.75-4A2.25 2.25 0 0 1 8 5.5a2.25 2.25 0 0 1 4-1.75a2.25 2.25 0 0 1 4 1.75a2.25 2.25 0 0 1 1.75 4M12 15.25v6.25");
}

</style>
