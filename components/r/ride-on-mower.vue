<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jm0h3yv0r"/><path class="bar2ni9_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ride-on-mower" /></template>
<style>
.bar2ni9_y {
  d: path("M3 10h10.5l7 2v1H15v5h-3v-8m-7.5 0l-1-4m9 4L14 5.5m-2 0h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm0h3yv0r {
  d: path("M2.75 16.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m14.5 1a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
