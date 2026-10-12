<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jugg-dbvr"/><path class="jw-jxxbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:outlet-eco" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jugg-dbvr {
  width: 15px;
  height: 18.5px;
  x: 4.5px;
  y: 2.75px;
  rx: 3.5px;
}

.jw-jxxbop {
  d: path("M9.5 6.25v3m5-3v3M8.75 18c.25-3.32 1.95-4.75 6.5-4.75C15 16.57 13.3 18 8.75 18");
}

</style>
