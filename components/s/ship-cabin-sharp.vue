<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ezcyjlz2t"/><path class="dnzubn_1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ship-cabin-sharp" /></template>
<style>
.dnzubn_1p {
  d: path("M7.75 9.5h1v1h-1Zm4 0h1v1h-1Zm4 0h1v1h-1Zm-8.5 7.75V13.5h2v3.75m-6.5 0h18.5L19.5 20.4l-.396.824l-.914.026H5.81l-.914-.026L4.5 20.4Zm1.5 0h15.5");
}

.ezcyjlz2t {
  d: path("M4.25 6.5h15.5v10.75H4.25zm-1.5 0h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
