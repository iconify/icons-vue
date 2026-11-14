<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ca2lj1bve"/><path class="u5i_ior8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-crying" /></template>
<style>
.ca2lj1bve {
  d: path("M5.25 8.75a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0M5 21.5c0-2 3-3.25 7-3.25s7 1.25 7 3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5i_ior8k {
  d: path("M9.5 6c.5 1 1.25 1.75 1.25 2.5a1.25 1.25 0 0 1-2.5 0C8.25 7.75 9 7 9.5 6m5 0c.5 1 1.25 1.75 1.25 2.5a1.25 1.25 0 0 1-2.5 0c0-.75.75-1.5 1.25-2.5M10 13q2-2.5 4 0");
}

</style>
