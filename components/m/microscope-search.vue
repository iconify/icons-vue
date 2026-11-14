<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic3g9o4vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microscope-search" /></template>
<style>
.ic3g9o4vm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.5h.5A1.75 1.75 0 0 1 9.5 4.25v5A1.75 1.75 0 0 1 7.75 11h-.5A1.75 1.75 0 0 1 5.5 9.25v-5A1.75 1.75 0 0 1 7.25 2.5M9.5 5c5 0 6.5 6 3 10v2.371m0 .2v.929m-9-4.5h6m-6 4.5h9m2.75-1a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
