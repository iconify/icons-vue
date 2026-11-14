<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u5pq7kmoc"/><path class="fd-rjozmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sunlight-shade" /></template>
<style>
.fd-rjozmo {
  d: path("M11.5 9.75a3.5 3.5 0 1 1 5.75 3.5M15 4.5V2.75m4.5 3.5L20.75 5M10.5 6.25L9.25 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5pq7kmoc {
  d: path("M6 20.75h10.5a3.75 3.75 0 0 0 0-7.5a5.5 5.5 0 0 0-10.5 1a3.25 3.25 0 0 0 0 6.5");
}

</style>
