<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hwsal5q-o"/><path class="g8wdkzbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-split" /></template>
<style>
.g8wdkzbot {
  d: path("M12 6.5a5.5 5.5 0 0 1 0 11Zm0 5.5H8.25M12 12L9.5 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwsal5q-o {
  cx: 12px;
  cy: 12px;
  r: 8px;
}

</style>
