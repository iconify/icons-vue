<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8575h_aq"/><path class="kb8mlz4ju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volunteer-firefighter" /></template>
<style>
.kb8mlz4ju {
  d: path("M8.5 9v1.5a3.5 3.5 0 0 0 7 0V9M4 21.5c0-3 3.5-4.5 8-4.5s8 1.5 8 4.5M10 9V6.75l2-1.25l2 1.25V9");
}

.p8575h_aq {
  d: path("M5.5 9a6.5 6.5 0 0 1 13 0m-16 1.25Q2.5 9 4 9h16q1.5 0 1.5 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
