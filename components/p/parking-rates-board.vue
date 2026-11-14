<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j6eq4wbvs"/><path class="w7iy3qb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-rates-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6eq4wbvs {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v7a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V6A3.5 3.5 0 0 1 6 2.5m6 14v5");
}

.w7iy3qb8j {
  d: path("M6 13.75v-8.5h2.5a2.5 2.5 0 0 1 0 5H6M17.5 7.5c0-.75-.75-1.25-1.75-1.25S14 6.75 14 7.75c0 2 3.5 1.25 3.5 3.5c0 1-.75 1.5-1.75 1.5S14 12.25 14 11.5m1.75-6.25v8.5");
}

</style>
