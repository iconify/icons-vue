<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpb2uww8m"/><path class="xy19zcb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-viewing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpb2uww8m {
  d: path("M6 3.5h5.5A3.5 3.5 0 0 1 15 7v2.5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5V7A3.5 3.5 0 0 1 6 3.5");
}

.xy19zcb3g {
  d: path("m15.871 6.098l3.5-1.616A1.5 1.5 0 0 1 21.5 5.844v4.812a1.5 1.5 0 0 1-2.129 1.362l-3.5-1.616A1.5 1.5 0 0 1 15 9.04V7.46a1.5 1.5 0 0 1 .871-1.362m-1.144 11.457l2.25-2.1a1.5 1.5 0 0 1 2.046 0l2.25 2.1a1.5 1.5 0 0 1 .477 1.097v1.598a1.5 1.5 0 0 1-1.5 1.5h-4.5a1.5 1.5 0 0 1-1.5-1.5v-1.598a1.5 1.5 0 0 1 .477-1.097");
}

</style>
