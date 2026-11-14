<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht60b0_rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pho-bowl" /></template>
<style>
.ht60b0_rj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18c0 5.25-4 9-9 9s-9-3.75-9-9Zm10.5 0l4-8m-1 8L21 4M5 11c0-3.5 2-5.5 5-5.5c0 3-2 5.5-5 5.5Z");
}

</style>
