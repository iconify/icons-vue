<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zo-pglouc"/><rect class="czklmx4bq"/><rect class="hlut1ob9o"/><rect class="q50ovcblk"/><path class="vfjucy2sr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swot" /></template>
<style>
.czklmx4bq {
  width: 8px;
  height: 8px;
  x: 13.25px;
  y: 2.75px;
  rx: 1.75px;
}

.hlut1ob9o {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q50ovcblk {
  width: 8px;
  height: 8px;
  x: 13.25px;
  y: 13.25px;
  rx: 1.75px;
}

.vfjucy2sr {
  d: path("M6.75 4.88v3.75M4.88 6.75h3.75m6.75 0h3.75M6.75 19.25V15.5M5.12 17l1.63-1.5L8.38 17m8.87-1.5v2.25m0 1.75v.01");
}

.zo-pglouc {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.75px;
}

</style>
