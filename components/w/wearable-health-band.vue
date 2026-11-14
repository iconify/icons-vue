<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fp3metops"/><path class="brkfp8bde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wearable-health-band" /></template>
<style>
.brkfp8bde {
  fill: currentColor;
  d: path("M12 14.75c-1.5-1-2.75-2-2.75-3.5c0-1 .75-1.75 1.75-1.75c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c1 0 1.75.75 1.75 1.75c0 1.5-1.25 2.5-2.75 3.5");
}

.fp3metops {
  d: path("M11.5 7h1a5 5 0 0 1 5 5a5 5 0 0 1-5 5h-1a5 5 0 0 1-5-5a5 5 0 0 1 5-5m-3 0V3.5a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1V7m-7 10v3.5a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
