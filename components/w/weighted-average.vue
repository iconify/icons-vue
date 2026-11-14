<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xu1u_5i8q"/><path class="djszmub6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weighted-average" /></template>
<style>
.djszmub6y {
  fill: currentColor;
  d: path("M6 8.5h5v5H6ZM18.25 11h2.5v2.5h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xu1u_5i8q {
  d: path("M2 15h20m-10 .75l3 4.75H9Z");
}

</style>
