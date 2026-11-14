<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y-r2pdbdd"/><path class="apv_zrbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roundabout-exit-slight-left" /></template>
<style>
.apv_zrbsu {
  d: path("M9 3.5H5.75v3.25m7.5 9.25a5 5 0 0 1-5-5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-r2pdbdd {
  d: path("M13.25 21.5V16a5 5 0 1 0-3.5-8.5l-4-4");
}

</style>
