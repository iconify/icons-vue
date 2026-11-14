<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh0e_kb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mine-reclamation" /></template>
<style>
.mh0e_kb7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C6 16 18 16 21.5 20.5ZM12 17V7m0 5c-3.5 0-5-2.5-5-5c2.5 0 5 1.5 5 5Zm0-2.5c0-3.5 2.5-6 5-6c0 2.5-1.5 6-5 6Zm-10 11h20");
}

</style>
