<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i0gcltbvb"/><path class="rcs8o5hox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:model-stack" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0gcltbvb {
  width: 13px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 2.5px;
}

.rcs8o5hox {
  d: path("M9.25 11.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5M6 5.75h10.25a2.5 2.5 0 0 1 2.5 2.5V18M9.25 2.75h9.5a2.5 2.5 0 0 1 2.5 2.5v9.5");
}

</style>
