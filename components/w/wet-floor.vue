<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipy80z73n"/><path class="x4rdkjzzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wet-floor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipy80z73n {
  d: path("M10.25 3h3.5q1.5 0 1.84 1.46l3.57 15.08Q19.5 21 18 21H6q-1.5 0-1.16-1.46L8.41 4.46Q8.75 3 10.25 3");
}

.x4rdkjzzs {
  d: path("M12 8.5c1.75 2 2.5 3.25 2.5 4.5a2.5 2.5 0 0 1-5 0c0-1.25.75-2.5 2.5-4.5M8.5 18h7");
}

</style>
