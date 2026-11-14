<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g5ympcw9t"/><path class="zkhwpxbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stomach" /></template>
<style>
.g5ympcw9t {
  d: path("M11 7.5c2-1.5 8.5-1.5 8.5 5c0 5-4 8-8.5 8c-4 0-6.5-2.5-6.5-5.5c0-1.5 1-2.5 2.5-2.5c2 0 2-2.5 2-3.5Zm-1-5v5.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zkhwpxbsy {
  d: path("M8.5 17c3 .25 6.5-1.5 7.5-5");
}

</style>
