<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjsxm-brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-park-and-ride" /></template>
<style>
.yjsxm-brt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5h11V19H10Zm0 7.5h11m-8.5 8v2.5m6-2.5v2.5M2.5 6A2.25 2.25 0 1 0 7 6a2.25 2.25 0 1 0-4.5 0Zm2.25 2.25V21.5");
}

</style>
