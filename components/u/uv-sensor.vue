<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ym_viizjx"/><path class="kgnfirb-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:uv-sensor" /></template>
<style>
.kgnfirb-y {
  d: path("M10 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 6V3M6 8.5l-2-2m14 2l2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ym_viizjx {
  d: path("M6.5 14.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
