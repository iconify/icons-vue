<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ll76k-wyk"/><path class="y2tldfb9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-waving" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ll76k-wyk {
  cx: 10px;
  cy: 6.25px;
  r: 2px;
}

.y2tldfb9t {
  d: path("M10 11v5.25m-2.25 5l2.25-5l2.25 5M10 12l-2.75 3.5M10 12l3.75-1.5L15 6.25m3.25-3A4.5 4.5 0 0 1 20 7");
}

</style>
