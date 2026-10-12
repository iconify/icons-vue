<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbfinhhea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermometer-lab-sharp" /></template>
<style>
.vbfinhhea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.69 3.49L7.43 13.75a3.75 3.75 0 1 0 2.82 2.82L20.51 6.31l1.297-1.515l-2.82-2.82zm-2.12 2.12l1.24 1.24m-3.36.88l1.24 1.24m-3.36.88l1.24 1.24");
}

</style>
