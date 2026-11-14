<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2fz9pc-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parquet-floor" /></template>
<style>
.g2fz9pc-n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9.25l4.5-4.5l4.5 4.5l4.5-4.5l4.5 4.5m-18 5l4.5-4.5l4.5 4.5l4.5-4.5l4.5 4.5m-18 5l4.5-4.5l4.5 4.5l4.5-4.5l4.5 4.5m-18-10v10m4.5-14.5v10m4.5-5.5v10m4.5-14.5v10m4.5-5.5v10");
}

</style>
