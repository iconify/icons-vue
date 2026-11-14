<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k45z4bbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-growth-ruler" /></template>
<style>
.k45z4bbvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15h8l-1 6.5h-6Zm12-12.5h5v19h-5ZM7.5 15v-3.5c-.25-2.5-1.75-4-4-4c0 2.25 1.5 4 4 4c.25-2.75 1.75-4.5 4-4.5c0 2.5-1.5 4.5-4 4.5m8-4.5H18m-2.5 5H18m-2.5 5H18");
}

</style>
