<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rnlu42bqp"/><path class="rt55fg0rb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voting-booth" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnlu42bqp {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 2.75px;
  rx: 1px;
}

.rt55fg0rb {
  d: path("M4.5 5.75h15v10.5a1 1 0 0 1-1 1h-13a1 1 0 0 1-1-1Zm4 0v11.5M12 5.75v11.5m3.5-11.5v11.5m-6.25 0v4m5.5-4v4");
}

</style>
