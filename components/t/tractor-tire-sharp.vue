<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uqqznmb-j"/><path class="j-72f2a6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tractor-tire-sharp" /></template>
<style>
.j-72f2a6j {
  d: path("m6 5.5l6 3l6-3m-12 5l6 3l6-3m-12 5l6 3l6-3M2.75 12H6m12 0h3.25");
}

.uqqznmb-j {
  d: path("M6 2.75h12v18.5H6z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
