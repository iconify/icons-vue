<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pil_37b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wisteria" /></template>
<style>
.pil_37b0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19m-18 0a3 3 0 0 0 1 5a3 3 0 0 0 1.25 5A3.5 3.5 0 0 0 7 20a3.5 3.5 0 0 0 1.25-6A3 3 0 0 0 9.5 9a3 3 0 0 0 1-5m3 0a3 3 0 0 0 1 4.5a3 3 0 0 0 1.25 4a3.5 3.5 0 0 0 1.25 5a3.5 3.5 0 0 0 1.25-5a3 3 0 0 0 1.25-4a3 3 0 0 0 1-4.5");
}

</style>
