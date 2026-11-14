<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q8iswmbrr"/><path class="cj8vdcbcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:remit-bank-deposit" /></template>
<style>
.cj8vdcbcf {
  d: path("m14.25 17.5l7.25-3.25l-3.25 7l-1.5-2.5Zm2.5 1.25l4.75-4.5");
}

.q8iswmbrr {
  d: path("M15.1 21.5H4.5v-19h15v9.6m-11-9.6V17m0 .7v3.8m3-14.5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
