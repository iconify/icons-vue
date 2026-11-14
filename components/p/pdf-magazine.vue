<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uecmt_b0z"/><path class="orvwi5bgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pdf-magazine" /></template>
<style>
.orvwi5bgn {
  d: path("M8 9.5h8v6H8Zm4 9h.01");
}

.uecmt_b0z {
  d: path("M4 2.5h16v19H4Zm4 4h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
