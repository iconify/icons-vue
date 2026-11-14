<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rstmxj7tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-catchment" /></template>
<style>
.rstmxj7tj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5h18c0 4.5-4 8-9 8s-9-3.5-9-8Zm9-11s-3 3.25-3 5a3 3 0 0 0 6 0c0-1.75-3-5-3-5ZM5.5 4v5m13-5v5");
}

</style>
