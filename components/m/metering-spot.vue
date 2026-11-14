<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7a150bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:metering-spot" /></template>
<style>
.b7a150bbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5v-2a2 2 0 0 1 2-2h3m9 0h3a2 2 0 0 1 2 2v2m0 7v2a2 2 0 0 1-2 2h-3m-9 0h-3a2 2 0 0 1-2-2v-2m6-3.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm3.5 0h.01");
}

</style>
