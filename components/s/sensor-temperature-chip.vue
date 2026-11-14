<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh_xt1b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sensor-temperature-chip" /></template>
<style>
.kh_xt1b9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h11v8H3Zm2.5 8v4m3-4v4m3-4v4m5.5-6V6a1.75 1.75 0 0 1 3.5 0v8a3.25 3.25 0 1 1-3.5 0Z");
}

</style>
