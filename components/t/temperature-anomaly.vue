<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_ijkpkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temperature-anomaly" /></template>
<style>
.oy_ijkpkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 13.75V5a2.5 2.5 0 0 1 5 0v8.75a4.25 4.25 0 1 1-5 0Zm2.5 3.5V7.5M2.5 12h4m11 0h4");
}

</style>
