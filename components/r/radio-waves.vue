<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2ssc0ycu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-waves" /></template>
<style>
.k2ssc0ycu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12h.01m3.437-2.893a4.5 4.5 0 0 1 0 5.786m3.516-7.768a8.5 8.5 0 0 1 0 9.75m-10.41-1.982a4.5 4.5 0 0 1 0-5.786m-3.516 7.768a8.5 8.5 0 0 1 0-9.75");
}

</style>
