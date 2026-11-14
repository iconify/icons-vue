<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lrcv07b5f"/><path class="n1cia05ds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tare-weight" /></template>
<style>
.lrcv07b5f {
  d: path("M6.5 3h11c0 3-1.5 5.25-3.5 6h-4c-2-.75-3.5-3-3.5-6ZM4 9h16m-8 0v2.75m-7.5 0h15l2 9.75h-19Z");
}

.n1cia05ds {
  d: path("M10 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
