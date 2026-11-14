<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1stwjskw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:signpost-big" /></template>
<style>
.i1stwjskw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5h12l3 2.25l-3 2.25h-12Zm13 7.5h-12l-3 2.25l3 2.25h12ZM12 8v3m0 4.5v6");
}

</style>
