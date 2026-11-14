<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vgt2cab1q"/><path class="jzrrdv0we"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:overhead-crane" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzrrdv0we {
  d: path("M11 4h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 13 7h-2a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 11 4m1 3v2.5M9.5 12L12 9.5l2.5 2.5m-4.25 0h3.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 10.25 12");
}

.vgt2cab1q {
  d: path("M3 21.5V4h18v17.5");
}

</style>
