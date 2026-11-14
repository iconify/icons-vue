<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5g3-zdyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pen-holder" /></template>
<style>
.u5g3-zdyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11h13v8a2 2 0 0 1-2 2h-9a2 2 0 0 1-2-2ZM9 11L8 3.5m4 7.5V2.5m3 8.5l1-7.5");
}

</style>
