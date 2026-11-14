<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yyi3fhysh"/><path class="wdo-tu5od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-clearance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wdo-tu5od {
  d: path("M6.788 8.288a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3.267 4.949l6.188-.176");
}

.yyi3fhysh {
  d: path("M6.325 4.575h4.597a1.75 1.75 0 0 1 1.237.513l8.503 8.503a1.75 1.75 0 0 1 0 2.475l-4.596 4.596a1.75 1.75 0 0 1-2.475 0l-8.503-8.503a1.75 1.75 0 0 1-.513-1.237V6.325a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
