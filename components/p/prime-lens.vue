<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l3zbf3bov"/><rect class="sfz8h1bgm"/><path class="yw3aekblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prime-lens" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3zbf3bov {
  d: path("M8.75 7.5h-1.5a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h1.5Z");
}

.sfz8h1bgm {
  width: 6px;
  height: 16.5px;
  x: 8.75px;
  y: 3.75px;
  rx: 2.5px;
}

.yw3aekblp {
  d: path("M11.75 3.75v16.5M17.25 7q2.5 5 0 10");
}

</style>
