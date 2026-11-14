<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-h7isb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:succession-plan" /></template>
<style>
.u-h7isb6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.224 19H5L3 6.5L7.75 11L12 4l4.25 7L21 6.5l-1.048 6.552M15 18h6m-2.5-2.5L21 18l-2.5 2.5");
}

</style>
