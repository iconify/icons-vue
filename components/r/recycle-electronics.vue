<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csuwj7b_r"/><path class="eq06gab4x"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recycle-electronics" /></template>
<style>
.csuwj7b_r {
  d: path("M7.125 4.5h4.75A2.625 2.625 0 0 1 14.5 7.125v4.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 4.5 11.875v-4.75A2.625 2.625 0 0 1 7.125 4.5m.375 0V2m4 2.5V2m-4 12.5V17m-3-9.5H2m2.5 4H2m12.5-4H17");
}

.eq06gab4x {
  d: path("M9 7.5h1A1.5 1.5 0 0 1 11.5 9v1a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 10V9A1.5 1.5 0 0 1 9 7.5m11.75 11A2.75 2.75 0 1 1 18 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

</style>
