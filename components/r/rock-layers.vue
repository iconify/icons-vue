<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5v327f3q"/><path class="qkxt6wb5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rock-layers" /></template>
<style>
.b5v327f3q {
  d: path("M3 20V7l4-2.5L11 6l4-2.5l6 3V20Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qkxt6wb5o {
  d: path("M3 11c3-1.5 6 1.5 9 0s6 1.5 9 0M3 15.5c3-1.5 6 1.5 9 0s6 1.5 9 0");
}

</style>
