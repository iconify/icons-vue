<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiie_nmai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:out-of-office" /></template>
<style>
.tiie_nmai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21V4.5A1.5 1.5 0 0 1 5 3h9a1.5 1.5 0 0 1 1.5 1.5V21m-13 0h13M11 12h10.5m-3-3l3 3l-3 3");
}

</style>
