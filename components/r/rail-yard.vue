<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ic31tfbct"/><rect class="gbmp-207x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rail-yard" /></template>
<style>
.gbmp-207x {
  width: 7.25px;
  height: 4px;
  x: 14px;
  y: 3px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic31tfbct {
  d: path("M2.75 5h10m-10 7h18.5m-18.5 7h18.5M5.75 5l7 7m-.5 0l7 7");
}

</style>
