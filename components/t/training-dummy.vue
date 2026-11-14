<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xpkdjsbmt"/><path class="wwfaeeh7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:training-dummy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwfaeeh7j {
  d: path("M7.5 5v14.5a4.5 1.75 0 0 0 9 0V5m-9 4.5c-3.75 0-3.75 5 0 5m9-5c3.75 0 3.75 5 0 5");
}

.xpkdjsbmt {
  d: path("M7.5 5a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0");
}

</style>
