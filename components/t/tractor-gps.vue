<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eh4paxbat"/><path class="y-pq-8kkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tractor-gps" /></template>
<style>
.eh4paxbat {
  d: path("M3.875 13.75h2.5a1.375 1.375 0 0 1 1.375 1.375A1.375 1.375 0 0 1 6.375 16.5h-2.5A1.375 1.375 0 0 1 2.5 15.125a1.375 1.375 0 0 1 1.375-1.375m3.875 0V10a.75.75 0 0 1 .75-.75h3.75l1 5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-pq-8kkz {
  d: path("M7.75 17.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-5.5 1.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m15.75-9c.05.1-2.95-2.5-3-4.75a3 3 0 0 1 6 0c.05 2.25-2.95 4.85-3 4.75M18 5h.01");
}

</style>
