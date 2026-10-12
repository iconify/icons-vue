<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gd_6yioib"/><path class="svrcuxb5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ruler-school" /></template>
<style>
.gd_6yioib {
  width: 18.5px;
  height: 7.5px;
  x: 2.75px;
  y: 12.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.svrcuxb5r {
  d: path("M6.25 12.75v2.75m3.25-2.75v1.75m3.25-1.75v2.75M16 12.75v1.75M5.25 3.75h10.5l4.75 2.5l-4.75 2.5H5.25a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2");
}

</style>
