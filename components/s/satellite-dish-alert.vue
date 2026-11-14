<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="str8y69mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:satellite-dish-alert" /></template>
<style>
.str8y69mu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5a7 7 0 0 0 10 10Zm5 5l4-4m0-3a3 3 0 0 1 3 3m-3-6a6 6 0 0 1 6 6M18 14.75v3.5M18 21h.01");
}

</style>
