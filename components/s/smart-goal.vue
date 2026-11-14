<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwzald1en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-goal" /></template>
<style>
.cwzald1en {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a4.25 4.25 0 1 0 8.5 0A4.25 4.25 0 1 0 2 12Zm4.25 0h.01m7.24-7l2.25 2l4.75-3.5m-7 8l2.25 2L20.5 10m-7 8l2.25 2l4.75-3.5");
}

</style>
