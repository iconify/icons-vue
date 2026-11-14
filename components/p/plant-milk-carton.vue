<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ozpfiwb3l"/><path class="khgb6kjrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-milk-carton" /></template>
<style>
.khgb6kjrn {
  d: path("M9.5 17.5c0-3.5 2-6 5-6c0 3.5-2 6-5 6Z");
}

.ozpfiwb3l {
  d: path("m7 8l2-4.5h6L17 8v12.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5Zm0 0h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
