<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vc0b30blo"/><path class="i4td9xbxm"/><rect class="qnl0m8b0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:telegraph-key" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4td9xbxm {
  d: path("M5.5 16.75v-3.5m0 0l11-1.75M13 16.75v-2.5");
}

.qnl0m8b0w {
  width: 5.5px;
  height: 3.5px;
  x: 15.75px;
  y: 8.25px;
  rx: 1.75px;
}

.vc0b30blo {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 16.75px;
  rx: 1.5px;
}

</style>
