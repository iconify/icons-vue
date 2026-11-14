<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yv350jbsg"/><path class="a29ib3d7y"/><path class="dgsvu7bga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:returns-cage" /></template>
<style>
.a29ib3d7y {
  d: path("M10 9h3a1.75 1.75 0 0 1 0 3.5h-2.5");
}

.dgsvu7bga {
  d: path("M11.25 7.75L10 9l1.25 1.25m-6 10.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m11 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yv350jbsg {
  d: path("M5.25 2.5h13.5a1.75 1.75 0 0 1 1.75 1.75v12.5a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 5.25 2.5m2.25 0v16m9-16v16m-13-12h17m-17 8h17");
}

</style>
