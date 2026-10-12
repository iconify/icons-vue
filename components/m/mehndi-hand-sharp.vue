<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vnh_fzn6i"/><path class="nksf2ybha"/><path class="ua92hsbdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mehndi-hand-sharp" /></template>
<style>
.nksf2ybha {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.44 13.71l.27.7l.19.46l.49-.07l.75-.1l.49-.07l-.31.39l-.46.59l-.31.39l.31.39l.46.59l.31.4l-.49-.08l-.75-.1l-.49-.07l-.19.46l-.27.7l-.19.46l-.19-.46l-.27-.7l-.19-.46l-.49.07l-.75.1l-.49.08l.31-.4l.46-.59l.31-.39l-.31-.39l-.46-.59l-.31-.39l.49.07l.75.1l.49.07l.19-.46l.27-.7l.19-.46z");
}

.ua92hsbdx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 9h.01M10 6h.01m2.49-.5h.01m2.49 1h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vnh_fzn6i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 14.5V6.75h2.5V8V3.5h2.5v1.25V3h2.5v2.25V4h2.5v8.5l1.6-1.6a1.4 1.4 0 0 1 2 2l-3.6 4.35a5.5 5.5 0 0 1-3.75 4h-.75a5.5 5.5 0 0 1-5.5-5.5Z");
}

</style>
