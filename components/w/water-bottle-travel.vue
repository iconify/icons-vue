<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd1xnnbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-bottle-travel" /></template>
<style>
.gd1xnnbpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5h4V6c0 1 3 1.5 3 4v9a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-9c0-2.5 3-3 3-4ZM7 14h10");
}

</style>
