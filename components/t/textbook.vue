<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1oqy_-_m"/><path class="k33le7bgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:textbook" /></template>
<style>
.g1oqy_-_m {
  d: path("M4.75 18.75V5.25a2.5 2.5 0 0 1 2.5-2.5h10a2 2 0 0 1 2 2v11.5H6.75a2 2 0 0 0-2 2Zm0 0a2.5 2.5 0 0 0 2.5 2.5h12v-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k33le7bgw {
  d: path("M8.75 6.25h6.5v4.25h-6.5Z");
}

</style>
