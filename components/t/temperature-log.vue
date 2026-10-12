<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cqrntgb-g"/><path class="y1wf1dc1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:temperature-log" /></template>
<style>
.cqrntgb-g {
  width: 10.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1wf1dc1w {
  d: path("M5.75 7h5m-5 3.5h5m-5 6l1.75-2L9 15.75l2-2.25m5.75-9a1.5 1.5 0 0 1 3 0v10.1a2.5 2.5 0 1 1-3 0Z");
}

</style>
