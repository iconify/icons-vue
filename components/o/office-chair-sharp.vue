<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1dsi4bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-chair-sharp" /></template>
<style>
.u1dsi4bam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.75h9.5v7h-9.5zm4.75 7V13m-7.25 0h14.5v3H4.75zM12 16v2.75m-5.75 2.5l5.75-2.5l5.75 2.5");
}

</style>
