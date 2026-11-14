<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gorrxnp8o"/><path class="y_c3f5biq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:red-blood-cell" /></template>
<style>
.gorrxnp8o {
  d: path("M2.5 12a9.5 6.75 0 1 0 19 0a9.5 6.75 0 1 0-19 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_c3f5biq {
  d: path("M7.5 11a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0M5 15.5c2 1.75 4.5 2.5 7 2.5");
}

</style>
