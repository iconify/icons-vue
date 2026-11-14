<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uw7ldw55n"/><path class="onms97b1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:panel-left" /></template>
<style>
.onms97b1e {
  d: path("M17 16.5L14.5 19l2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uw7ldw55n {
  d: path("M11.6 18H2.5V2.5H21v13.7M9 2.5V18m12.5 1h-7");
}

</style>
