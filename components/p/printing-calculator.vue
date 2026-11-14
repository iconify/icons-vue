<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c2ryph7jz"/><path class="mn7c2w1gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printing-calculator" /></template>
<style>
.c2ryph7jz {
  d: path("M6.5 9.5h11A3.5 3.5 0 0 1 21 13v4a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17v-4a3.5 3.5 0 0 1 3.5-3.5m-1 0v-6H13v6m-4.75-3h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mn7c2w1gh {
  d: path("M14.25 12.5h2.5A1.25 1.25 0 0 1 18 13.75A1.25 1.25 0 0 1 16.75 15h-2.5A1.25 1.25 0 0 1 13 13.75a1.25 1.25 0 0 1 1.25-1.25M6.5 13.75h.01m3.49 0h.01M6.5 17.5h.01m3.49 0h.01m5.49.25h.01");
}

</style>
