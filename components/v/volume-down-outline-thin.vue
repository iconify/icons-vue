<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmjqszbgk"/><path class="p3nkycb4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volume-down-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmjqszbgk {
  d: path("M8 9H3v6h5l5 5V4Z");
}

.p3nkycb4i {
  d: path("M15.5 7.67a5 5 0 0 1 0 8.66");
}

</style>
