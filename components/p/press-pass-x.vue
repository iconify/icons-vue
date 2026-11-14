<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0n_bqfjj"/><path class="e_gx2bbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:press-pass-x" /></template>
<style>
.e_gx2bbia {
  d: path("M9.75 10.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8.5 16.5h4m3-1l5 5m0-5l-5 5");
}

.i0n_bqfjj {
  d: path("M10 5.5v-3h4v3m-1.4 16H5v-16h14v7.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
