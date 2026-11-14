<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp33nkbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tsunami-warning" /></template>
<style>
.gp33nkbkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20C4 10.5 8.5 4 14.5 4c3.5 0 6 2 6 5c-2.5-1.5-6.5-.5-7 3m-11 8h11m4.5-5.5V18m0 3h.01");
}

</style>
