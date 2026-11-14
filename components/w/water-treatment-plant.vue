<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u8cb6cblw"/><path class="mxk96qi3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-treatment-plant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mxk96qi3a {
  d: path("M10.5 7.5s-3 3.5-3 5.5a3 3 0 0 0 6 0c0-2-3-5.5-3-5.5");
}

.u8cb6cblw {
  d: path("M9.75 3h1.5a5.25 5.25 0 0 1 5.25 5.25v7.5A5.25 5.25 0 0 1 11.25 21h-1.5a5.25 5.25 0 0 1-5.25-5.25v-7.5A5.25 5.25 0 0 1 9.75 3M3 21h15m-1.5-7h3a1.5 1.5 0 0 1 1.5 1.5V18");
}

</style>
