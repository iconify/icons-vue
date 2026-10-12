<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6-nqabik"/><rect class="oevhb-xbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oven-mitt" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oevhb-xbf {
  width: 11.5px;
  height: 2.75px;
  x: 7.5px;
  y: 18.5px;
  rx: 1.25px;
}

.w6-nqabik {
  d: path("M18.25 16.25V8.5a4.75 4.75 0 0 0-9.5 0v1.6L6.6 8.7a1.9 1.9 0 0 0-2.4 2.9l4.55 4.65Zm-7-6.25h4");
}

</style>
