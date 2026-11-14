<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zxktk1bym"/><path class="hczcjubti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:petticoat" /></template>
<style>
.hczcjubti {
  d: path("M6 10q2 1.5 4 0q2 1.5 4 0q2 1.5 4 0M4.5 15.5q2.5 1.5 5 0q2.5 1.5 5 0q2.5 1.5 5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxktk1bym {
  d: path("M8.5 3h7l2.5 7l1.5 5.5L21 21q-2.25 1.5-4.5 0q-2.25 1.5-4.5 0q-2.25 1.5-4.5 0q-2.25 1.5-4.5 0l1.5-5.5L6 10Z");
}

</style>
