<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2aln052h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quality-control-chem" /></template>
<style>
.s2aln052h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v6L4.5 19q-.75 2 1.5 2h7.806m3.658-5.702L14 9V3M8.5 3h7m-.75 15l2 2L21 15.75");
}

</style>
