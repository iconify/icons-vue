<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgv2cgbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stratus-cloud" /></template>
<style>
.wgv2cgbbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19c0-3-2-4.5-5-4.5c-1.5-2.5-7-3-9 0c-3 0-5 1.75-5 4.5ZM6 18h12");
}

</style>
