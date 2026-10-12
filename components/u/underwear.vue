<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qkfutpbeu"/><path class="vunhaob3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:underwear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qkfutpbeu {
  width: 17.5px;
  height: 3.5px;
  x: 3.25px;
  y: 4.5px;
  rx: 1.25px;
}

.vunhaob3t {
  d: path("M3.25 8h17.5v2.25C17 10.75 14.5 14 14 19.5h-4c-.5-5.5-3-8.75-6.75-9.25Z");
}

</style>
