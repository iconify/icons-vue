<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="btp_l8qzh"/><path class="a30jequir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:muffler" /></template>
<style>
.a30jequir {
  d: path("M9.5 7v10m5-10v10M2.75 10h2.5m13.5 4h2.5");
}

.btp_l8qzh {
  width: 13.5px;
  height: 10px;
  x: 5.25px;
  y: 7px;
  rx: 5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
