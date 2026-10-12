<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mbz7cwb5y"/><path class="hjldrqjiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soda-can-sharp" /></template>
<style>
.hjldrqjiq {
  d: path("M6 14q3-2.25 6 0c3 2.25 4 1.5 6 0");
}

.mbz7cwb5y {
  d: path("M6 5.25h12v16H6zm2.5-2.5h7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
