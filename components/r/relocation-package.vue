<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi61tjbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:relocation-package" /></template>
<style>
.bi61tjbnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5h13V21h-13Zm0 3.5h13M9 10.5V14m9.5-2s-3-2.75-3-5.25a3 3 0 0 1 6 0c0 2.5-3 5.25-3 5.25Z");
}

</style>
