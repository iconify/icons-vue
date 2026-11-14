<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h21r3j6vl"/><path class="yol9b_wkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patent-certificate" /></template>
<style>
.h21r3j6vl {
  d: path("M6.5 17.5h-2v-15h15v15h-2M8.5 6h7m-7 3.5H13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yol9b_wkz {
  d: path("M10.25 18a3 3 0 1 1 3.5 0l1 3.5L12 20.25L9.25 21.5Z");
}

</style>
