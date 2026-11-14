<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sdh33fbir"/><path class="a-_1x_bcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:streetball" /></template>
<style>
.a-_1x_bcv {
  d: path("M7 14.75L9 21h6l2-6.25m-7.5-9.5h5v3h-5Z");
}

.sdh33fbir {
  d: path("M3.5 2.5h17V11h-17ZM7 14.75a5 1 0 1 0 10 0a5 1 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
