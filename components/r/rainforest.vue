<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tw42zj86m"/><path class="ybd_9ccga"/><circle class="pbch-3bfg"/><path class="nrq2xk4ea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rainforest" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrq2xk4ea {
  d: path("M7 17.25v4M13 15v6.25m5-4.5v4.5M4.75 2.75l-.75 2m5.5-2l-.75 2m11 .5l-.75 2");
}

.pbch-3bfg {
  cx: 7px;
  cy: 13px;
  r: 4.25px;
}

.tw42zj86m {
  d: path("M8.72 9.11a4.5 4.5 0 1 1 2.25 5.41a4.25 4.25 0 0 0-2.25-5.41");
}

.ybd_9ccga {
  d: path("M17.5 10.29a3.25 3.25 0 1 1-2.57 4.28a4.5 4.5 0 0 0 2.57-4.28");
}

</style>
