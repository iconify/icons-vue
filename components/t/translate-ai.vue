<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ig0owebfi"/><path class="lqrw-xtir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:translate-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ig0owebfi {
  width: 11px;
  height: 11px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

.lqrw-xtir {
  d: path("m5.75 10.75l2.5-5l2.5 5M6.6 9h3.3m5.85-4.75H17a2.5 2.5 0 0 1 2.5 2.5V8.5M17.75 7l1.75 1.75L21.25 7M16 12.25q.54 3.96 4.5 4.5q-3.96.54-4.5 4.5q-.54-3.96-4.5-4.5q3.96-.54 4.5-4.5");
}

</style>
