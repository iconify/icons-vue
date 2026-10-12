<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o1j78wiwv"/><path class="f3iw4acio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mic-settings" /></template>
<style>
.f3iw4acio {
  d: path("M4.75 10.75a7.25 7.25 0 0 0 14.5 0M12 18v3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1j78wiwv {
  width: 7.5px;
  height: 11.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 3.75px;
}

</style>
