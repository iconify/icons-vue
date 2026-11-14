<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wy687pumk"/><path class="y7cl5n_xv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:matcha-bowl" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wy687pumk {
  d: path("M2.5 5.5h19c0 6.5-4 11-9.5 11S2.5 12 2.5 5.5Zm6 13.75h7");
}

.y7cl5n_xv {
  d: path("M6 9q3-1.5 6 0t6 0");
}

</style>
