<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ujlqkug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:palm-scan-sharp" /></template>
<style>
.h9ujlqkug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5V2.75H7.5m9 0h4.75V7.5m0 9v4.75H16.5m-9 0H2.75V16.5m3.25-3v-6h3V9V6h3v2v-1.5h3V9V7.5h3v6a6 6 0 0 1-12 0ZM9 9v2.5m3-4v4M15 8v3.5");
}

</style>
