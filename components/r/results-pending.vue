<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxj346bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:results-pending" /></template>
<style>
.cxj346bwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12m-12 19h12M7.5 2.5v3c0 3 4.5 4.5 4.5 6.5s-4.5 3.5-4.5 6.5v3m9-19v3c0 3-4.5 4.5-4.5 6.5s4.5 3.5 4.5 6.5v3");
}

</style>
