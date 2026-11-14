<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev6i1bbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pit-crew-member" /></template>
<style>
.ev6i1bbcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.639 0 3.13.335 4.342.932M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm12.75 7.5a2 2 0 1 0 2.25 2.25M18 18l-2.75 2.75");
}

</style>
