<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hymrft2cg"/><path class="reky_0b3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seed-sack-sharp" /></template>
<style>
.hymrft2cg {
  d: path("M8.75 7.75C5.75 10 3.5 13 3.5 16.25c0 3 2 5 5 5h7c3 0 5-2 5-5c0-3.25-2.25-6.25-5.25-8.5Zm.25 0L7.25 3.5l2.25.75h5l2.25-.75L15 7.75Z");
}

.reky_0b3e {
  d: path("M12 12.5c1.75 1.25 1.75 4.25 0 5.5c-1.75-1.25-1.75-4.25 0-5.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
