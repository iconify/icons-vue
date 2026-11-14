<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vj6gys4wc"/><path class="nsdj28bru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newsletter-stats" /></template>
<style>
.nsdj28bru {
  d: path("M6.5 16.5L8.75 13l2 1.75l2.75-4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vj6gys4wc {
  d: path("M17 20H5.5A2.5 2.5 0 0 1 3 17.5v-12A1.5 1.5 0 0 1 4.5 4h11A1.5 1.5 0 0 1 17 5.5V18a2 2 0 0 0 4 0V9h-4ZM6.5 7.5h7");
}

</style>
