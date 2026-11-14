<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivqh2e2hn"/><path class="nd_w0cbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:whistling" /></template>
<style>
.ivqh2e2hn {
  d: path("M2.5 15.5c0-4 2.75-6.25 5-5.25l1.25 1l1.25-1c2.25-1 5 1.25 5 5.25c0 3.5-3 6-6.25 6S2.5 19 2.5 15.5Z");
}

.nd_w0cbad {
  d: path("M6.5 16a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0Zm10.25-7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0v-6Q22 3 22 5.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
