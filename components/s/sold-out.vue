<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjtirjbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sold-out" /></template>
<style>
.rjtirjbek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h8.5l9.5 9.5l-8.5 8.5L3 11.5Zm3.5 3.5h.01m2.74 2.75l5.5 5.5m0-5.5l-5.5 5.5");
}

</style>
