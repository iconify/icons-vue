<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8esbtbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:walk-score" /></template>
<style>
.u8esbtbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1.5 3l-1.5 6m0 0l-.433 1.011m-.552 1.287L7.5 20.5m3-7l.704.845m1.532 4.535L12.5 21m-.75-12.25L8.5 11.5M12 8.75l3 2.5m2.75 3l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L17.75 19.5l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
