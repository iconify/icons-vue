<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j_4l8cbnk"/><path class="qx8iffo1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j_4l8cbnk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 2h3c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l1 3c.366 1.101-.505 2.286-1.242 3.023l-1 1a.414.414 0 0 0 0 .586l3 3a.414.414 0 0 0 .586 0l1-1c.737-.737 1.922-1.608 3.023-1.242l3 1c.586.196 1.031.66 1.302 1.203c.271.541.382 1.145.382 1.746v3c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.9 16.9 0 0 1-5.404-3.643a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2");
}

.qx8iffo1k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16C5.105 13.105 3 9.418 3 5a2 2 0 0 1 2-2h3c.995 0 1.8.403 2 1l1 3c.153.46-.234 1.234-1 2l-1 1a1.414 1.414 0 0 0 0 2l1 2m7-1l3 1c.597.2 1 1.005 1 2v3a2 2 0 0 1-2 2c-2.878 0-5.667-.67-8-2m-9 3L22 2");
}

</style>
