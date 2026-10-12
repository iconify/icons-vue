<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xjkqd2bbf"/><rect class="xldnaxbku"/><path class="n3c1q1b5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mailbox-parcel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n3c1q1b5d {
  d: path("M12 12.75v1.75");
}

.xjkqd2bbf {
  d: path("M5.25 20.25V9.5a6.75 6.75 0 0 1 13.5 0v10.75a1 1 0 0 1-1 1H6.25a1 1 0 0 1-1-1m3.5-11.5h6.5");
}

.xldnaxbku {
  width: 6px;
  height: 5px;
  x: 9px;
  y: 12.75px;
  rx: 0.75px;
}

</style>
