<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw87a-n1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-keys" /></template>
<style>
.mw87a-n1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7 3l9 9m-3-3l-2.5 2.5m5 0l-2.25 2.25");
}

</style>
