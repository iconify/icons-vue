<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wixxmolyr"/><path class="gk6llfbgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vacuum-tube" /></template>
<style>
.gk6llfbgc {
  d: path("M9.5 15.5v-6h5v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wixxmolyr {
  d: path("M6.5 18.5V9a5.5 5.5 0 0 1 11 0v9.5Zm3 0v3m5-3v3");
}

</style>
