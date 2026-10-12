<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="tpuy9wb5l"/><path class="bbdtuib-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:music-gen" /></template>
<style>
.bbdtuib-a {
  d: path("M9.25 17.5v-14c1.5 2.25 4 3 5.5 3.25M17 10q.51 3.74 4.25 4.25q-3.74.51-4.25 4.25q-.51-3.74-4.25-4.25Q16.49 13.74 17 10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tpuy9wb5l {
  cx: 6.25px;
  cy: 17.5px;
  r: 3px;
}

</style>
