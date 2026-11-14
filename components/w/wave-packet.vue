<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj-blcm7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wave-packet" /></template>
<style>
.cj-blcm7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5h19m-19 0c1.25-3 2.25-3 3.5 0c1.25 6 2.75 6 4 0c1.25-10 2.75-10 4 0c1.25 6 2.75 6 4 0c1.25-3 2.25-3 3.5 0");
}

</style>
