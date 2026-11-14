<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sld7-ybdq"/><path class="cag0a2bjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-ball-machine" /></template>
<style>
.cag0a2bjg {
  d: path("M4 18.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M16.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M5.25 11.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sld7-ybdq {
  d: path("M6 6h4a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 10 17H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 6");
}

</style>
