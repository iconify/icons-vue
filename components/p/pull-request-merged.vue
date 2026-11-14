<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o6yrvmboa"/><path class="irb0kkhdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pull-request-merged" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irb0kkhdy {
  d: path("M6 6.5c0 3.5 6 3 6 6.5m6-6.5c0 3.5-6 3-6 6.5m0 0v4.5m-2 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.o6yrvmboa {
  d: path("M4 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m12 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
