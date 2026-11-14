<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a97zbqv6h"/><path class="kd_63s7_c"/><path class="vqz4qzz_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:music-club" /></template>
<style>
.a97zbqv6h {
  d: path("M9 2.5V8m-6.5 6.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kd_63s7_c {
  d: path("M2.5 14.5a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0");
}

.vqz4qzz_r {
  d: path("M6.5 14.5a2.5 6.5 0 1 0 5 0a2.5 6.5 0 1 0-5 0M17 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3 0V2.5");
}

</style>
