<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hni2cpqww"/><path class="ps_q4_1lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:unrestricted-fund" /></template>
<style>
.hni2cpqww {
  d: path("M6.5 10h10a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5h-10A3.5 3.5 0 0 1 3 17.5v-4A3.5 3.5 0 0 1 6.5 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ps_q4_1lc {
  d: path("M20 13.5h-3.25a1.75 1.75 0 0 0 0 3.5H20M5.5 4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7.75.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
