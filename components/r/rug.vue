<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pm92krw3p"/><path class="t971a7bxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rug" /></template>
<style>
.pm92krw3p {
  d: path("M8 7.5h12.5l-4.5 9H3.5Z");
}

.t971a7bxj {
  d: path("M9.75 10.25H16l-1.75 3.5H8ZM7.25 9H5.5m.25 3H4m.25 3H2.5m17.25-6h1.75m-3.25 3H20m-3.25 3h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
