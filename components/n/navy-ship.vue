<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bqg419ble"/><rect class="yc-79nbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:navy-ship" /></template>
<style>
.bqg419ble {
  d: path("M2.75 15h18.5l-2.4 4.5a1.5 1.5 0 0 1-1.3.75H6.45a1.5 1.5 0 0 1-1.3-.75ZM8 14.5v-3q0-.5.5-.5H9q.5 0 .5-.5V9q0-.5.5-.5h2.25q.5 0 .5.5v1.5q0 .5.5.5h.5q.5 0 .5.5v3q0 .5-.5.5H8.5q-.5 0-.5-.5m3-6V4.75m-2.25-1.5c.75 1.5 3.75 1.5 4.5 0M16.75 15v-1.5a1.5 1.5 0 0 1 1.5-1.5h.5a1.5 1.5 0 0 1 1.5 1.5V15ZM20 12.75l1.25-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yc-79nbmt {
  width: 2.5px;
  height: 2.5px;
  x: 3px;
  y: 12.5px;
  rx: 0.75px;
}

</style>
