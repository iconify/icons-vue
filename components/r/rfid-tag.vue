<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><path class="v1gjv4oug"/><rect class="tjy3rxbwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rfid-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0_gb6qzx {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

.tjy3rxbwv {
  width: 3.5px;
  height: 3px;
  x: 10.25px;
  y: 10.5px;
  rx: 0.5px;
}

.v1gjv4oug {
  d: path("M7 8.25h10a1 1 0 0 1 1 1v5.5a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-5.5a1 1 0 0 1 1-1");
}

</style>
