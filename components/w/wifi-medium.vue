<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="djqthtavr"/><path class="tribtvy6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wifi-medium" /></template>
<style>
.djqthtavr {
  d: path("M8.111 14.611a5.5 5.5 0 0 1 7.778 0M4.222 10.722a11 11 0 0 1 15.556 0");
}

.tribtvy6q {
  fill: currentColor;
  d: path("M10.5 18.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
