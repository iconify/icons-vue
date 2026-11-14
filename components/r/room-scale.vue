<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx3wpkp7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:room-scale" /></template>
<style>
.mx3wpkp7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5h-3l-1 3.25m9-3.25h3l1 3.25m-15 6l-1 3.75h4m14-3.75l1 3.75h-4m-8-9h5l2 5h-9Z");
}

</style>
