<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfijxvd7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oscillation" /></template>
<style>
.vfijxvd7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4h6m-3 0v11m-2.5 2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-2.75-1a13.5 13.5 0 0 1-4-2.75m0 2.5v-2.5h2.5m12 2.75a13.5 13.5 0 0 0 4-2.75m0 2.5v-2.5h-2.5");
}

</style>
