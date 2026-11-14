<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccv2m6imn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:needle" /></template>
<style>
.ccv2m6imn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.303 3.868l2.829 2.829l-3.536 3.535l-2.828-2.828Zm-2.121 4.95l-9.9 9.9m7.779-12.021l4.242 4.242");
}

</style>
