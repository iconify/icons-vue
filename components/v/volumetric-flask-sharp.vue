<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh7ns2b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:volumetric-flask-sharp" /></template>
<style>
.hh7ns2b5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4v6.1L16.96 14H7.04L10 8.85ZM7.04 14h9.92l2.24 3.9l1.865 3.328l-3.815.022H6.79l-3.815-.022L4.84 17.9ZM8.5 2.75h7");
}

</style>
