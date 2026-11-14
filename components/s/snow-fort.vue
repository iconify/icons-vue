<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y139g6buf"/><path class="h49rigjlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snow-fort" /></template>
<style>
.h49rigjlx {
  d: path("M9 19.5V14a3 3 0 0 1 6 0v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y139g6buf {
  d: path("M2.5 19.5v-15H6v3h3.5v-3h5v3H18v-3h3.5v15Z");
}

</style>
