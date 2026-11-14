<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz9v16zuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-dog-park" /></template>
<style>
.vz9v16zuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 7.75a3 3 0 1 1 4.75-2a3 3 0 1 1-2 4.75l-5.75 5.75a3 3 0 1 1-4.75 2a3 3 0 1 1 2-4.75Z");
}

</style>
