<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ptleyrb5p"/><path class="siyw-bchj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swing-set-sharp" /></template>
<style>
.ptleyrb5p {
  d: path("M3.25 21.25L6.5 3.75h11l3.25 17.5M10 3.75v10.5m4-10.5v10.5");
}

.siyw-bchj {
  d: path("M8.5 14.25h7v2.25h-7z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
