<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zcucs5bud"/><path class="xg6rmt6wa"/><path class="y5z5ctpzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signal-booster-pole" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg6rmt6wa {
  fill: currentColor;
  d: path("M10.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.y5z5ctpzp {
  d: path("M15.447 6.107a4.5 4.5 0 0 1 0 5.786m2.298-7.714a7.5 7.5 0 0 1 0 9.642m-9.192-1.928a4.5 4.5 0 0 1 0-5.786m-2.298 7.714a7.5 7.5 0 0 1 0-9.642");
}

.zcucs5bud {
  d: path("M8 21.5h8m-4 0V9");
}

</style>
