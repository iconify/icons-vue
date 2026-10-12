<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u9830ccam"/><path class="a464gbbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:viking-helmet-sharp" /></template>
<style>
.a464gbbma {
  d: path("M6.2 11.9C4 11.25 2.75 9.25 2.75 5.75C4 8 6.25 9.25 8.8 9.75Zm11.6 0c2.2-.65 3.45-2.65 3.45-6.15c-1.25 2.25-3.5 3.5-6.05 4Z");
}

.u9830ccam {
  d: path("M4.75 16.25a7.25 7.25 0 0 1 14.5 0v2.25h-6v2.75h-2.5V18.5h-6v-.75Zm1-1h12.5M12 10v5.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
