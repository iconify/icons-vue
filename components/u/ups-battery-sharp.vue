<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kupfe8ior"/><path class="l1gzk17yp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ups-battery-sharp" /></template>
<style>
.kupfe8ior {
  d: path("M5 2.75h14v18.5H5zm3.5 3h7");
}

.l1gzk17yp {
  d: path("m13 9.5l-3 4.25h4L11 18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
