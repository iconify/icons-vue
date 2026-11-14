<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj-w0_f1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-dog-park" /></template>
<style>
.rj-w0_f1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 7.75a3 3 0 1 1 4.75-2a3 3 0 1 1-2 4.75l-5.75 5.75a3 3 0 1 1-4.75 2a3 3 0 1 1 2-4.75Z");
}

</style>
