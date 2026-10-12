<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wb2zzvnfq"/><path class="qnu8o3bcj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pot" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnu8o3bcj {
  d: path("M4.25 13h-1.5m17 0h1.5M3.75 7.5h16.5m-9.75 0V6a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v1.5");
}

.wb2zzvnfq {
  width: 15.5px;
  height: 11.25px;
  x: 4.25px;
  y: 10px;
  rx: 2.5px;
}

</style>
