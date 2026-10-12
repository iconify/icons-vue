<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kikkge11l"/><path class="ht_-hsp_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:purse-sharp" /></template>
<style>
.ht_-hsp_k {
  d: path("M7.75 9.25v-2a4.25 4.25 0 0 1 8.5 0v2m-6 4h3.5");
}

.kikkge11l {
  d: path("M6.25 9.25h11.5l1.592-.001l.358 1.551l1.5 7.5l.538 2.939l-2.988.011H5.25l-2.988-.011L2.8 18.3l1.5-7.5l.358-1.551z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
