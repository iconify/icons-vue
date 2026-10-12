<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e8_44acdy"/><rect class="zovmjxbfg"/><rect class="x5p0plbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:polaroid-stack" /></template>
<style>
.e8_44acdy {
  d: path("M2.75 17.75V4.25a1.5 1.5 0 0 1 1.5-1.5h13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5p0plbhw {
  width: 10px;
  height: 8.5px;
  x: 8.75px;
  y: 8.75px;
  rx: 0.75px;
}

.zovmjxbfg {
  width: 15px;
  height: 15px;
  x: 6.25px;
  y: 6.25px;
  rx: 1.5px;
}

</style>
