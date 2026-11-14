<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ib98ybatb"/><path class="aydsmo20i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:receipt-dollar" /></template>
<style>
.aydsmo20i {
  d: path("M14.25 8.75C14 8 13.2 7.5 12 7.5c-1.25 0-2.25.7-2.25 1.75c0 2.25 4.5 1.5 4.5 4c0 1.05-1 1.75-2.25 1.75s-2.1-.5-2.25-1.25m2.25-8V7.5m0 7.5v1.75");
}

.ib98ybatb {
  d: path("M5 3h14v18l-3.5-2l-3.5 2l-3.5-2L5 21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
