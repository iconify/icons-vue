<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_zna7ayv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toilet-sharp" /></template>
<style>
.h_zna7ayv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75h6.5v6h-6.5zm-.5 8.5h18.5a7 7 0 0 1-6.5 7l.5 3h-6.5L9.5 18a7 7 0 0 1-6.75-6.75Z");
}

</style>
