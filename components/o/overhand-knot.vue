<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e7j-t_b0r"/><path class="hze1ucbjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:overhand-knot" /></template>
<style>
.e7j-t_b0r {
  d: path("M2.5 18c5 0 10-1 13.25-4.5a5.5 5.5 0 1 0-7.5 0");
}

.hze1ucbjj {
  d: path("M8.25 13.5C11.5 17 16.5 18 21.5 18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
