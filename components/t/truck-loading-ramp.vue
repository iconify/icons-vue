<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l4uy84b3e"/><circle class="raw51vchv"/><circle class="pk8yrhbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:truck-loading-ramp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4uy84b3e {
  d: path("M8.25 6A1.25 1.25 0 0 1 9.5 4.75h6A1.25 1.25 0 0 1 16.75 6v3.25h2.1a1.5 1.5 0 0 1 1.25.67l.9 1.35a1.5 1.5 0 0 1 .25.83V14a1 1 0 0 1-1 1h-12Zm8.5 3.25V15m-8.5.5v5q0 .5-.5.5h-4.5q-.5 0-.16-.37l4.82-5.26q.34-.37.34.13");
}

.pk8yrhbxx {
  cx: 18.5px;
  cy: 19.5px;
  r: 1.5px;
}

.raw51vchv {
  cx: 12.75px;
  cy: 19.5px;
  r: 1.5px;
}

</style>
