<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8iv-1b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oil-depot" /></template>
<style>
.q8iv-1b9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5V13a2.5 2.5 0 0 1 5 0v7.5m2 0V8a2.5 2.5 0 0 1 5 0v12.5m2 0V11a2.5 2.5 0 0 1 5 0v9.5M2 20.5h20M7.5 16h2m5 0h2");
}

</style>
