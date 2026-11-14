<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pncql6baz"/><path class="aj4og5d9p"/><path class="e5a3io06l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:receipt-check-exit" /></template>
<style>
.aj4og5d9p {
  d: path("M14.5 21.75v-7.5h6.25v7.5");
}

.e5a3io06l {
  d: path("M14.5 14.25L18 15.5v5.25l-3.5 1Z");
}

.pncql6baz {
  d: path("M11.707 20.832L8.5 19L5 21V3h14v8.4M8.5 7.5h7m-7 3.5h3.2m1.9 0h1.9m-7 3.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
