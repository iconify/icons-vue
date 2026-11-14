<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8crs_b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:report-binder" /></template>
<style>
.e8crs_b4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h13v19h-13ZM3 6.5h6.25M3 12h6.25M3 17.5h6.25m3.25-2V13m2.5 2.5V9m2.5 6.5V11");
}

</style>
