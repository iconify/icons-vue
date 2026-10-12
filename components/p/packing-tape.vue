<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="z0rxcxb0v"/><path class="lwx762bnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:packing-tape" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwx762bnj {
  d: path("M6 9.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m3.25 6.5h12L20 17.5l1.25 1.75h-12Z");
}

.z0rxcxb0v {
  cx: 9.25px;
  cy: 9.25px;
  r: 6.5px;
}

</style>
