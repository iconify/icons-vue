<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="y3becndqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:off-plan-property" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

.y3becndqb {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M7.5 13l1.75-1.5m1.25-1L12 9.25m0 0l1.5 1.25m1.25 1L16.5 13M8 14.5V16m0 1.5v1h1.5m1.5 0h2m1.5 0H16v-1m0-1.5v-1.5");
}

</style>
