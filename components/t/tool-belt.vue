<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pc6xdh1ui"/><rect class="cmwwpccgo"/><path class="rfg831bqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tool-belt" /></template>
<style>
.cmwwpccgo {
  width: 5.5px;
  height: 5.5px;
  x: 9.25px;
  y: 4px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pc6xdh1ui {
  d: path("M9.25 5H4a1.25 1.25 0 0 0-1.25 1.25v1A1.25 1.25 0 0 0 4 8.5h5.25Zm5.5 0H20a1.25 1.25 0 0 1 1.25 1.25v1A1.25 1.25 0 0 1 20 8.5h-5.25Z");
}

.rfg831bqe {
  d: path("M8 12H3.75q-1 0-1 1.25M5.5 12v9.25m11.23-9.52a2.5 2.5 0 1 0 3.54 0M18.5 16v5.25");
}

</style>
