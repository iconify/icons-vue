<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lysj6h72e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:menu-search" /></template>
<style>
.lysj6h72e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6.5h17M3.5 12h7m-7 5.5h6M13 15a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.25 2.25l2.25 2.25");
}

</style>
