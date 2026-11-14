<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iio-4ccvw"/><path class="rs1wtuo8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spatial-video" /></template>
<style>
.iio-4ccvw {
  d: path("M2.5 7h15v11h-15Z");
}

.rs1wtuo8z {
  d: path("M6 7V6a2 2 0 0 1 2-2h11.5a2 2 0 0 1 2 2v6.5a2 2 0 0 1-2 2h-2M8 9.75l5 2.75l-5 2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
