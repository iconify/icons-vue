<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v3pq_9b2x"/><circle class="qme-dacyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salad" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qme-dacyk {
  cx: 7.25px;
  cy: 8px;
  r: 2px;
}

.v3pq_9b2x {
  d: path("M4 12.5h16a.75.75 0 0 1 .75.8A8 8 0 0 1 16 19.45V20a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-.55a8 8 0 0 1-4.75-6.15a.75.75 0 0 1 .75-.8m8.5-2.5C11 7 12 4 15.75 2.75c1.75 3 .25 6-3.25 7.25");
}

</style>
