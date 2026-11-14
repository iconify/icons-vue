<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tus49qbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neural-network" /></template>
<style>
.tus49qbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm0 15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm14-7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM5 7v10M7.25 5.75l9.5 5m-9.5 7.5l9.5-5");
}

</style>
