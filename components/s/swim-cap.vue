<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xwdo12bgl"/><rect class="corng9b1x"/><rect class="t3ao9d5hv"/><path class="o06cdlbtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swim-cap" /></template>
<style>
.corng9b1x {
  width: 3.5px;
  height: 2.75px;
  x: 6.5px;
  y: 13px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o06cdlbtu {
  d: path("M3.25 14.375H6.5m3.5 0h4m3.5 0h3.25");
}

.t3ao9d5hv {
  width: 3.5px;
  height: 2.75px;
  x: 14px;
  y: 13px;
  rx: 1px;
}

.xwdo12bgl {
  d: path("M3.25 17.25v-3.5a8.75 8.75 0 0 1 17.5 0v3.5a1.5 1.5 0 0 1-1.5 1.5H4.75a1.5 1.5 0 0 1-1.5-1.5M12 5v5.5");
}

</style>
