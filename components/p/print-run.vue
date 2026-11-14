<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjw799hur"/><path class="ae2dzwofq"/><path class="cyibsnbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:print-run" /></template>
<style>
.ae2dzwofq {
  d: path("M8 9V6h9v6");
}

.cyibsnbck {
  d: path("M11 6V3h8v9m-9.5 4.5h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mjw799hur {
  d: path("M5.066 12h13.868a1.75 1.75 0 0 1 1.726 2.038l-.916 5.5A1.75 1.75 0 0 1 18.018 21H5.982a1.75 1.75 0 0 1-1.726-1.462l-.916-5.5A1.75 1.75 0 0 1 5.066 12M5 12V9h9v3");
}

</style>
