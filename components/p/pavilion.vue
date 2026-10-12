<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt7knlb4k"/><rect class="c7ucf6g9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pavilion" /></template>
<style>
.c7ucf6g9v {
  width: 18.5px;
  height: 2.75px;
  x: 2.75px;
  y: 18.5px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yt7knlb4k {
  d: path("M9.6 3.25h4.8q.6 0 1 .45l2.7 3.1q.4.45.99.56l1.57.28q.59.11.35.66l-.27.65q-.24.55-.84.55H4.1q-.6 0-.84-.55l-.27-.65q-.24-.55.35-.66l1.57-.28q.59-.11.99-.56l2.7-3.1q.4-.45 1-.45M6 9.5v9m12-9v9m-8.25-9V12m4.5-2.5V12");
}

</style>
