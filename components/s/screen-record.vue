<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d7lirwbtl"/><circle class="aehem7bjh"/><path class="guhbvob-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:screen-record" /></template>
<style>
.aehem7bjh {
  cx: 12px;
  cy: 10.25px;
  r: 2.75px;
}

.d7lirwbtl {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

.guhbvob-p {
  d: path("M12 16.75v3.5m-3.75 0h7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
