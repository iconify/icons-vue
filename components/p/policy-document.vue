<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="ng7-6glby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:policy-document" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ng7-6glby {
  d: path("m12 5.5l3.25 1.2v2.55c0 2.1-1.4 3.6-3.25 4.65c-1.85-1.05-3.25-2.55-3.25-4.65V6.7Zm-3.75 11h7.5m-7.5 2.25h4.5");
}

.x00qgzx7x {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
