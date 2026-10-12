<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-l7mpb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:syrup-spoon-sharp" /></template>
<style>
.c-l7mpb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75c1 1.3 2 2.3 2 3.4a2 2 0 0 1-4 0c0-1.1 1-2.1 2-3.4Zm-5 8.75h10a5 4.75 0 0 1-10 0Zm10 0h3.5l5-4.25");
}

</style>
