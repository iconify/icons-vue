<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1a4eqmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:study-leave" /></template>
<style>
.hg1a4eqmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5h6a2 2 0 0 1 2 2v13a2 2 0 0 0-2-2H4Zm16 0h-6a2 2 0 0 0-2 2v13a2 2 0 0 1 2-2h6Z");
}

</style>
