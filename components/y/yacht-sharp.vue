<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu78jbrfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yacht-sharp" /></template>
<style>
.zu78jbrfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5h17.5l-.33.94l-1.09 3.12l-.33.94H6.25l-.57-.82l-2.36-3.36l-.57-.82zm4 0l1.75-4h5.75l3 4Zm4.75-4V5.25M2.75 20.5L5.06 19l2.31 1.5l2.315 1.503L12 20.5l2.308-1.498L16.63 20.5l2.317 1.495L21.25 20.5");
}

</style>
