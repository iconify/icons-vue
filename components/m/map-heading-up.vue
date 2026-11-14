<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2n0t-bws"/><path class="mee2o7qts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-heading-up" /></template>
<style>
.mee2o7qts {
  d: path("M15.5 17.5L18 15l2.5 2.5");
}

.p2n0t-bws {
  d: path("M14.206 20.13L8.5 18.5l-6 2v-15l6-2l7 2l6-2v11.071M8.5 3.5v15m7-13v6.7M18 21v-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
