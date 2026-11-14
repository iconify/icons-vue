<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ecps-_83m"/><path class="dvah5fojk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:race-ticket" /></template>
<style>
.dvah5fojk {
  fill: currentColor;
  d: path("M6 5za1.5 1.5 0 0 1 1.5 1.5V7A1.5 1.5 0 0 1 6 8.5A1.5 1.5 0 0 1 4.5 7v-.5A1.5 1.5 0 0 1 6 5m6 0za1.5 1.5 0 0 1 1.5 1.5V7A1.5 1.5 0 0 1 12 8.5A1.5 1.5 0 0 1 10.5 7v-.5A1.5 1.5 0 0 1 12 5m6 0za1.5 1.5 0 0 1 1.5 1.5V7A1.5 1.5 0 0 1 18 8.5A1.5 1.5 0 0 1 16.5 7v-.5A1.5 1.5 0 0 1 18 5");
}

.ecps-_83m {
  d: path("M4.5 5h15a2 2 0 0 1 2 2v3a2 2 0 0 0 0 4v3a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-3a2 2 0 0 0 0-4V7a2 2 0 0 1 2-2m-2 3.5h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
