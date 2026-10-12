<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h52fsg23x"/><path class="aa5998bqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:money-bag-sharp" /></template>
<style>
.aa5998bqs {
  d: path("m13.71 13.04l-.435-1.08H10.29v1.33c0 1.77 3.56.99 3.56 2.88v1.36h-3.18l-.54-1.08M12 10.88v1.08m0 5.58v1.08");
}

.h52fsg23x {
  d: path("M9.5 8h5c3.5 2.5 6.25 5.75 6.25 8.75a4.5 4.5 0 0 1-4.5 4.5h-8.5a4.5 4.5 0 0 1-4.5-4.5c0-3 2.75-6.25 6.25-8.75Zm-.75-5.25h6.5l-1.5 3h-3.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
