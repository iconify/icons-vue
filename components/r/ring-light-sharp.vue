<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f4ari4irz"/><path class="btn2n2vep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ring-light-sharp" /></template>
<style>
.btn2n2vep {
  d: path("M10.75 8h2.5v3.5h-2.5zM12 16.75v4.5m-3.5 0h7");
}

.f4ari4irz {
  d: path("M19 9.75a7 7 0 1 1-14 0a7 7 0 1 1 14 0m-2.5 0a4.5 4.5 0 1 1-9 0a4.5 4.5 0 1 1 9 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
