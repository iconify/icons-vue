<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ttv105gdf"/><path class="o93bxhbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:validation-split-sharp" /></template>
<style>
.o93bxhbfb {
  d: path("m13.25 12.25l1.5 1.5l3-3");
}

.ttv105gdf {
  d: path("M9.75 5.25h-7v13.5h7Zm0 0h11.5v13.5H9.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
