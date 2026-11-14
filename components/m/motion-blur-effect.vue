<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz-d5ubxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:motion-blur-effect" /></template>
<style>
.nz-d5ubxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM2.5 9H7m-4.5 3h4m-4 3H7");
}

</style>
