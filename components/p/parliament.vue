<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="vi67undok"/><path class="k1yosrmpu"/><path class="zj3mh0bhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parliament" /></template>
<style>
.k1yosrmpu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15.5v3m2.75-3v3m2.75-3v3m2.75 2V8.25q0-.75.38-1.4l1.99-3.45q.38-.65.76 0l1.99 3.45q.38.65.38 1.4V20.5q0 .75-.75.75h-4q-.75 0-.75-.75");
}

.vi67undok {
  width: 11.25px;
  height: 8.75px;
  x: 2.75px;
  y: 12.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zj3mh0bhi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 10.5h.01");
}

</style>
