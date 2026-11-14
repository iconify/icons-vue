<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="skuayb02t"/><path class="f8o6kyb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-filter-tap" /></template>
<style>
.f8o6kyb-h {
  d: path("M14.5 9.5h5V16h-5Z");
}

.skuayb02t {
  d: path("M4 21.5h6m-3 0V8a5 5 0 0 1 10 0v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
