<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxqbxibrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:street-tap" /></template>
<style>
.kxqbxibrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 18.5v-15M6 3.5h5M8.5 8H14a2.5 2.5 0 0 1 2.5 2.5v1m-11 10l1.5-3h3l1.5 3Zm11-7L18 17a1.75 1.75 0 1 1-3 0Z");
}

</style>
