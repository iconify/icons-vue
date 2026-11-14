<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6kkl4t9v"/><path class="p15yvwq0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sports-jersey" /></template>
<style>
.p15yvwq0d {
  d: path("M10 11.5h4l-2.5 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6kkl4t9v {
  d: path("M8 3L3 6l1.5 4.5l2.5-1V21h10V9.5l2.5 1L21 6l-5-3c-.5 2-2.5 3-4 3S8.5 5 8 3Z");
}

</style>
