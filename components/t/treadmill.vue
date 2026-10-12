<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z_2nl4byy"/><path class="usvnlvbpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:treadmill" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.usvnlvbpc {
  d: path("M6 18.5h10.5m1-2.25l-2.75-11.5h4.5");
}

.z_2nl4byy {
  width: 17px;
  height: 4.5px;
  x: 2.75px;
  y: 16.25px;
  rx: 2.25px;
}

</style>
