<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t15qx2t4y"/><rect class="jdj0kb80h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:private-jet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdj0kb80h {
  width: 5px;
  height: 2.75px;
  x: 5.5px;
  y: 7.25px;
  rx: 1.25px;
}

.t15qx2t4y {
  d: path("M2.75 14.5V4.75h1.5L8.75 10h8c2.5 0 4.5 1 4.5 2.25s-2 2.25-4.5 2.25ZM12 12.25h.01m2.49 0h.01m2.49 0h.01M10.5 14.5L8 18.75");
}

</style>
