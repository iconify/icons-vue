<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ztlwh8j1u"/><path class="ml4fyvb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tag-barcode" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ml4fyvb8f {
  d: path("M6 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6-4v8m3-8v8m3-8v8");
}

.ztlwh8j1u {
  d: path("m3.04 11.1l3.45-5.75a1.75 1.75 0 0 1 1.501-.85H19.75a1.75 1.75 0 0 1 1.75 1.75v11.5a1.75 1.75 0 0 1-1.75 1.75H7.991a1.75 1.75 0 0 1-1.501-.85L3.04 12.9a1.75 1.75 0 0 1 0-1.8");
}

</style>
