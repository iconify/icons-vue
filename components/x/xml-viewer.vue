<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdo68vbgt"/><path class="wf2m-6bsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:xml-viewer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wf2m-6bsl {
  d: path("M14 2.5V7a2 2 0 0 0 2 2h4.5M8.75 12L6.5 14.75l2.25 2.75M12.5 12l-1 5.5m3.75-5.5l2.25 2.75l-2.25 2.75");
}

.xdo68vbgt {
  d: path("M6 2.5h8L20.5 9v10a2.5 2.5 0 0 1-2.5 2.5H6A2.5 2.5 0 0 1 3.5 19V5A2.5 2.5 0 0 1 6 2.5");
}

</style>
