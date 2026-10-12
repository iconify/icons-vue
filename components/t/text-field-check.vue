<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ppkmu3b3c"/><path class="w4jmn4blp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-field-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ppkmu3b3c {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 7px;
  rx: 2.5px;
}

.w4jmn4blp {
  d: path("M6.25 12h4.5m3-2.5v5");
}

</style>
