<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7imknk8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sequence-add" /></template>
<style>
.s7imknk8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5H12v4H3.5Zm0 7.5H12v4H3.5Zm0 7.5H12v4H3.5Zm4.25-11V10m0 4v3.5M18 15v6m-3-3h6");
}

</style>
