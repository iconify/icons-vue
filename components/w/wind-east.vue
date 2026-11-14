<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u01gepz4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wind-east" /></template>
<style>
.u01gepz4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h19m-3.25-3l3.25 3l-3.25 3M2.5 11H16a3 3 0 1 1-3 3M2.5 16h6a2.75 2.75 0 1 1-2.75 2.75");
}

</style>
