<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ep5eb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:screen-free-night" /></template>
<style>
.o-ep5eb8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11.1V2.5h8.6m1.9 5.9v3.5m-3.4 8.6H5v-1.6M16.5 3.5l-13 13m15.25-2.25a3.75 3.75 0 1 0 3 4.5a3 3 0 0 1-3-4.5Z");
}

</style>
