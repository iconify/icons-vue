<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to60pgldk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:x-ray-crystallography" /></template>
<style>
.to60pgldk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 6l3.5 3v6L12 18l-3.5-3V9Zm0 0v12M3.5 3.5L6 6m14.5-2.5L18 6M3.5 20.5L6 18m14.5 2.5L18 18");
}

</style>
