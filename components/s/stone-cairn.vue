<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwv0qfb8u"/><path class="s5bhbkbqu"/><path class="em02q19ku"/><path class="p_xfavb8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stone-cairn" /></template>
<style>
.cwv0qfb8u {
  d: path("M3.5 18a8.5 2.75 0 1 0 17 0a8.5 2.75 0 1 0-17 0");
}

.em02q19ku {
  d: path("M7.25 8a4.75 2.25 0 1 0 9.5 0a4.75 2.25 0 1 0-9.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_xfavb8z {
  d: path("M9 4a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0");
}

.s5bhbkbqu {
  d: path("M5.5 12.75a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0");
}

</style>
