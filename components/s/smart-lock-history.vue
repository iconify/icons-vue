<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="epm_c9bsg"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-lock-history" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.epm_c9bsg {
  d: path("M12.5 20.5v.5h-10V10h10v5.5M4.75 10V6.75a2.75 2.75 0 0 1 5.5 0V10M7.5 13.5v4m7.25.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
