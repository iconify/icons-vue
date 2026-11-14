<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u-7gfxb_q"/><path class="tbhs01bvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-filter-pitcher" /></template>
<style>
.tbhs01bvf {
  d: path("M15.75 7H18a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2.75m-7-11.5V9a1 1 0 0 0 1 1h2.5a1 1 0 0 0 1-1V3.5");
}

.u-7gfxb_q {
  d: path("M4.5 3.5H16l-1 17H7L6 7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
