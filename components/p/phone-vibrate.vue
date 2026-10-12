<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tn6uk8bcr"/><path class="tlv5q2bid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-vibrate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tlv5q2bid {
  d: path("M11 17.25h2m-7.75-8.5v6.5m-2.5-4.75v3m16-4.75v6.5m2.5-4.75v3");
}

.tn6uk8bcr {
  width: 8px;
  height: 16.5px;
  x: 8px;
  y: 3.75px;
  rx: 2px;
}

</style>
