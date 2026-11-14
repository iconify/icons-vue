<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z_fefwsuy"/><path class="qctfvgbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-mountain-top" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qctfvgbrd {
  d: path("m8.75 9l1.75 2.25l1.5-1.5l1.5 1.5L15.25 9");
}

.z_fefwsuy {
  d: path("m4.01 17.377l6.473-11.243a1.75 1.75 0 0 1 3.034 0l6.473 11.243A1.75 1.75 0 0 1 18.473 20H5.527a1.75 1.75 0 0 1-1.517-2.623");
}

</style>
