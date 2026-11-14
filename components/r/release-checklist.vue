<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vjh7ktbcs"/><path class="wf44hsaev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:release-checklist" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjh7ktbcs {
  d: path("M8 3.5h8A3.5 3.5 0 0 1 19.5 7v11.5A3.5 3.5 0 0 1 16 22H8a3.5 3.5 0 0 1-3.5-3.5V7A3.5 3.5 0 0 1 8 3.5");
}

.wf44hsaev {
  d: path("M10.5 2h3A1.5 1.5 0 0 1 15 3.5A1.5 1.5 0 0 1 13.5 5h-3A1.5 1.5 0 0 1 9 3.5A1.5 1.5 0 0 1 10.5 2m-3 7l1.25 1.25L11 8m2 1h3.5m-9 4.25l1.25 1.25L11 12.25m2 1h3.5m-9 4.25l1.25 1.25L11 16.5m2 1h3.5");
}

</style>
