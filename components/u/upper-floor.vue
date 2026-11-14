<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="us_qbfb0n"/><path class="jzufz2nqi"/><path class="z4xqf3bul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:upper-floor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzufz2nqi {
  fill: currentColor;
  d: path("M7.5 8.5h9A1.5 1.5 0 0 1 18 10v1.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 11.5V10a1.5 1.5 0 0 1 1.5-1.5");
}

.us_qbfb0n {
  d: path("M6 21.5v-13L12 3l6 5.5v13");
}

.z4xqf3bul {
  d: path("M2.5 21.5h19M6 17.25h12");
}

</style>
