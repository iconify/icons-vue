<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ru4tp72_w"/><path class="p1ykhfepk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:usp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1ykhfepk {
  d: path("m9 9l3 11.75L15 9");
}

.ru4tp72_w {
  d: path("M7 3.5h10L21.5 9L12 21L2.5 9ZM2.5 9h19");
}

</style>
