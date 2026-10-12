<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iuw410b5b"/><path class="wmndunb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mattress" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iuw410b5b {
  d: path("M7.5 6.25H20q1.25 0 1.25 1.25v4q0 1.25-.72 2.27l-2.06 2.96q-.72 1.02-1.97 1.02H4q-1.25 0-1.25-1.25v-4q0-1.25.72-2.27l2.06-2.96q.72-1.02 1.97-1.02");
}

.wmndunb5x {
  d: path("M2.75 11.25h15l3.5-5m-3.5 5v6.5M5.25 14.5c1.25-.75 2.5.75 3.75 0s2.5-.75 3.75 0");
}

</style>
