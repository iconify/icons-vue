<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_xc_lbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rain-crop" /></template>
<style>
.i_xc_lbgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10.5H17a3 3 0 0 0 0-6A5.5 5.5 0 0 0 7.25 6a2.25 2.25 0 0 0-.75 4.5Zm-1 2.75l-1 3.25m15-3.25l-1 3.25m-6.5 5v-5m0 2q-4 0-4-3.5q4 0 4 3.5Zm0-2q4 0 4-3.5q-4 0-4 3.5Z");
}

</style>
