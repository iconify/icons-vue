<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t4v88cc0u"/><path class="rnkzptjcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voice-id" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnkzptjcn {
  d: path("M5.75 10.5v3m3-5v7m3-4.5v2m4-5.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3m-2.5 8.75c0-1.6 1.1-2.75 2.5-2.75s2.5 1.15 2.5 2.75");
}

.t4v88cc0u {
  width: 18.5px;
  height: 15px;
  x: 2.75px;
  y: 4.5px;
  rx: 2.5px;
}

</style>
