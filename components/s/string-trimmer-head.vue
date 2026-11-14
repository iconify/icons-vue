<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eo3qh4btq"/><path class="dw8a45bhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:string-trimmer-head" /></template>
<style>
.dw8a45bhd {
  d: path("M10 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8 0c1.5 0 3 1 3.5 2.5M6 13.5c-1.5 0-3-1-3.5-2.5");
}

.eo3qh4btq {
  d: path("M6 13.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6-6V3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
