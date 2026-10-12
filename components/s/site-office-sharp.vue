<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kmd617-0l"/><path class="fseqo6blz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:site-office-sharp" /></template>
<style>
.fseqo6blz {
  d: path("M6 5.25h2.75v2.5H5.5v-2.5zm5.75 0h2.75v2.5h-3.25v-2.5zM6 16h3v2.5H5.5V16zm5.75 5.25V16h2.75v5.25m2.75-11h1.25l2.75 11");
}

.kmd617-0l {
  d: path("M2.75 2.75h14.5v7.5H2.75zm0 10.5h14.5v8H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
