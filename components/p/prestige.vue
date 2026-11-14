<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gpvivus0e"/><path class="sw3lbbchi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prestige" /></template>
<style>
.gpvivus0e {
  d: path("M13.226 16.141L11 14.75l-4 2.5q-1 .5-.75-.5l1.25-4.5L4 9q-1-.75.25-.75L8.75 8l1.75-4.5q.5-1 1 0L13.25 8l4.5.25Q19 8.25 18 9l-3.5 3.25l.9 3.241M18.25 15A3.25 3.25 0 1 1 15 18.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sw3lbbchi {
  d: path("m19.75 13.5l-1.5 1.5l1.5 1.5");
}

</style>
