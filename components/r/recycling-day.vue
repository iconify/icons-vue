<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuzslgydn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recycling-day" /></template>
<style>
.vuzslgydn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 4.75l3.75 6.5m-2-.75l2 .75l.25-2m-3.8 7.5H5.5M7 15.5l-1.5 1.25L7 18m-2.75-3.25l5.5-9.5m-2 .75l2-.75l.25 2m5 8.25h6v5.75h-6Zm0 2.25h6m-4.25-3.25V16m2.5-1.5V16");
}

</style>
