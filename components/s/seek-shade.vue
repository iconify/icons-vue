<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbgjfcbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seek-shade" /></template>
<style>
.pbgjfcbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11a9 8 0 0 1 18 0q-3-1.5-6 0q-3-1.5-6 0q-3-1.5-6 0Zm9-.75V19m-6 1a6 1.5 0 1 0 12 0a6 1.5 0 1 0-12 0Z");
}

</style>
