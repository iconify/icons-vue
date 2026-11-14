<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhnh3tban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sort-amount-down" /></template>
<style>
.rhnh3tban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4v16m-3-3l3 3l3-3m3-13H21v2.5h-8.5Zm0 6.75h6v2.5h-6Zm0 6.75H16V20h-3.5Z");
}

</style>
