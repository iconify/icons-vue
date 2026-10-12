<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nz26t1bjz"/><rect class="o_uquoy0g"/><rect class="p6h23nbls"/><path class="m_6v3nb8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:piano-keys" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_6v3nb8q {
  d: path("M9 16v2m6-2v2");
}

.nz26t1bjz {
  width: 18px;
  height: 12px;
  x: 3px;
  y: 6px;
  rx: 2px;
}

.o_uquoy0g {
  width: 2.5px;
  height: 7px;
  x: 7.75px;
  y: 6px;
  rx: 0.75px;
}

.p6h23nbls {
  width: 2.5px;
  height: 7px;
  x: 13.75px;
  y: 6px;
  rx: 0.75px;
}

</style>
