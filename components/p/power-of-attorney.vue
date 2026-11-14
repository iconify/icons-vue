<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b6jdfhbjn"/><path class="h-clnccpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-of-attorney" /></template>
<style>
.b6jdfhbjn {
  d: path("M13.492 15.786L10 21.5l-5.5-9l2-6.5h7l1.927 6.262M6.5 6V3h7v3M10 21.5V14");
}

.h-clnccpu {
  d: path("M8.5 12.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM16.25 16a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1.75 5.75a3.5 3 0 0 1 7 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
