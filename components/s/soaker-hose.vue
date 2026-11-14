<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ds448gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soaker-hose" /></template>
<style>
.n_ds448gh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8C7 3 10 3 12 7s5 4 9.5-1M6 14l-1.25 2.5a1.75 1.75 0 1 0 2.5 0Zm6 0l-1.25 2.5a1.75 1.75 0 1 0 2.5 0Zm6 0l-1.25 2.5a1.75 1.75 0 1 0 2.5 0Z");
}

</style>
