<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vfcwvdbfr"/><path class="e6zgfdcaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:school-bag" /></template>
<style>
.e6zgfdcaj {
  d: path("M5 8.25c0-3.75 3-5.5 7-5.5s7 1.75 7 5.5M2.75 12.5v.75A2.25 2.25 0 0 0 5 15.5h14a2.25 2.25 0 0 0 2.25-2.25v-.75M7 15.5V18m10-2.5V18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfcwvdbfr {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 8.25px;
  rx: 2.5px;
}

</style>
