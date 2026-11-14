<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvvrwesac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:opening-act" /></template>
<style>
.fvvrwesac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19m-19 0h4q0 8-4 11.5Zm19 0h-4q0 8 4 11.5ZM3 20.5h18M9.5 5.5h5v8h-5Zm2.5 8v7");
}

</style>
