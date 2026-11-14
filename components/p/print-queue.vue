<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n7_x_c0ff"/><path class="u4ersp0mk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:print-queue" /></template>
<style>
.n7_x_c0ff {
  d: path("M7 17H5.5a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H17v-3H7Zm-1-7V6.25h9.5V10");
}

.u4ersp0mk {
  d: path("M9 6.25V3h9.5v7M7 14h10v7H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
