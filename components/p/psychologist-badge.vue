<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yat2y3b4p"/><path class="c-lzd2y4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:psychologist-badge" /></template>
<style>
.c-lzd2y4y {
  d: path("M8.5 7.5v2a3.5 3.5 0 0 0 7 0v-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yat2y3b4p {
  d: path("m12 2.5l7.5 2.75V11c0 5-3 8.5-7.5 10.5c-4.5-2-7.5-5.5-7.5-10.5V5.25Zm0 4v11");
}

</style>
