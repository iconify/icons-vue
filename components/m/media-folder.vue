<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zd9fbdclh"/><path class="pnab-ubgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:media-folder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pnab-ubgf {
  d: path("m11.968 11.46l.868.473a1.5 1.5 0 0 1 0 2.634l-.868.473a1.5 1.5 0 0 1-2.218-1.317v-.946a1.5 1.5 0 0 1 2.218-1.317");
}

.zd9fbdclh {
  d: path("M2.5 7a2 2 0 0 1 2-2H9l2 2.5h8.5a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

</style>
