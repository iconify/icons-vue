<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc2fk5g0j"/><path class="icy19obja"/><path class="y4goolmub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:temperature-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icy19obja {
  fill: currentColor;
  d: path("M7 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.tc2fk5g0j {
  d: path("M6 13.25V5.5a3 3 0 0 1 6 0v7.75a4.75 4.75 0 1 1-6 0");
}

.y4goolmub {
  d: path("M9 17v-6.5M18 3q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3");
}

</style>
