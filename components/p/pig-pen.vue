<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hhkmqv_xz"/><rect class="ct1t_8g9k"/><path class="t2djhmb4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pig-pen" /></template>
<style>
.ct1t_8g9k {
  width: 5px;
  height: 3px;
  x: 9.5px;
  y: 8.5px;
  rx: 1.5px;
}

.hhkmqv_xz {
  d: path("M6 10.5a6 6 0 0 1 .8-3l-.55-3.75L9 5.3a6 6 0 0 1 6 0l2.75-1.55l-.55 3.75a6 6 0 0 1 .8 3v.5a6 3 0 0 1-12 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t2djhmb4l {
  d: path("M5 16v5.25M9.5 16v5.25m5-5.25v5.25M19 16v5.25m-15.75-2.5h17.5");
}

</style>
