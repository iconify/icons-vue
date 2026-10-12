<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="pb0hd7ocr"/><path class="gy7rnxzfe"/><path class="asybd-ykr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:putty-knife" /></template>
<style>
.asybd-ykr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 11.5h3q1 0 1.38.93l3.24 7.89q.38.93-.62.93h-11q-1 0-.62-.93l3.24-7.89q.38-.93 1.38-.93");
}

.gy7rnxzfe {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5.5h.01");
}

.pb0hd7ocr {
  width: 5px;
  height: 9px;
  x: 9.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
