<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ngil7h8zo"/><path class="s-7hf3bfc"/><rect class="dscc2eb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:refill-station" /></template>
<style>
.dscc2eb3w {
  width: 5.75px;
  height: 5.25px;
  x: 15.5px;
  y: 16px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngil7h8zo {
  width: 10px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

.s-7hf3bfc {
  d: path("M5.75 7h4m-4 3h4m3-3.25h5.5V9m0 1.5c.9 1.15 1.5 1.95 1.5 2.6a1.5 1.5 0 0 1-3 0c0-.65.6-1.45 1.5-2.6");
}

</style>
