<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljjv0qblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pond-pump" /></template>
<style>
.ljjv0qblb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13H15v8H2.5Zm6.25 0V9c0-3.75 2.5-6 5.75-6s5 2.5 5 6m0 3c1.25 1.5 1.75 2.5 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-1 .5-2 1.75-3.5Z");
}

</style>
