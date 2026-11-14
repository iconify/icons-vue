<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edqhlffyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:quiet-street" /></template>
<style>
.edqhlffyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 21L10 3m7.028 8.075L14 3m-2 2.5v2m0 3v2.7m2 2.8h1.75l2.5-2.25v7l-2.5-2.25H14Zm5.5.25l2.25 2.25m0-2.25L19.5 18.5");
}

</style>
