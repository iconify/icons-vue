<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z82lrzb-f"/><path class="qffntcb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-turnstile" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qffntcb-z {
  d: path("M10 5.5h4A1.5 1.5 0 0 1 15.5 7v1.5A1.5 1.5 0 0 1 14 10h-4a1.5 1.5 0 0 1-1.5-1.5V7A1.5 1.5 0 0 1 10 5.5m-1.75 8.25h.01m9.74 1L21 16v2.25c0 1.75-1.25 2.75-3 3.5c-1.75-.75-3-1.75-3-3.5V16Z");
}

.z82lrzb-f {
  d: path("M5 21.5v-18q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057T6 2.5h12q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T19 3.5v8.672M2.5 21.5h10.7");
}

</style>
