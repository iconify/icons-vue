<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpppw2bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-dry" /></template>
<style>
.xpppw2bpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10a9.5 7.5 0 0 1 19 0a3.25 2 0 0 0-6.25 0a3.25 2 0 0 0-6.5 0a3.25 2 0 0 0-6.25 0ZM9 12.75h6V15H9ZM8 15h8v6.5H8Z");
}

</style>
