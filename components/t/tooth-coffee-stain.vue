<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2528bfhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-coffee-stain" /></template>
<style>
.b2528bfhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.217 12.674l.033-.174c.5-1.75 1.75-3.25 1.75-5.75c0-2.25-1-4.25-3.5-4.25c-1.75 0-2.5 1-4 1s-2.25-1-4-1C4 2.5 3 4.5 3 6.75c0 2.5 1.25 4 1.75 5.75l1 5.25c.25 1.25 1.75 1.25 2 0l1-4c.214-1.071 2.448-1.224 3.24-.46m2.76 2.21h4.5V19A2.25 2.25 0 0 1 17 21.25A2.25 2.25 0 0 1 14.75 19Zm4.5 1a1.5 1.5 0 0 1 0 3");
}

</style>
