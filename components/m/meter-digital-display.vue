<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-brwyb-v"/><path class="kazf_80mh"/><path class="sxgd8saqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meter-digital-display" /></template>
<style>
.g-brwyb-v {
  d: path("M6.875 3.5h10.25A4.375 4.375 0 0 1 21.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 16.125v-8.25A4.375 4.375 0 0 1 6.875 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kazf_80mh {
  d: path("M7 6.25h10A1.75 1.75 0 0 1 18.75 8v3A1.75 1.75 0 0 1 17 12.75H7A1.75 1.75 0 0 1 5.25 11V8A1.75 1.75 0 0 1 7 6.25M8 9.5h2.5m2.75 0H16");
}

.sxgd8saqn {
  fill: currentColor;
  d: path("M10.75 16.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
