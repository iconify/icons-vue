<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_5t4jpxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spatial-resize" /></template>
<style>
.j_5t4jpxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.6 15.5H2.5v-13h15v9.2M5.5 19H10m4.5-4.5L21 21m-6.5-3v-3.5H18m-.5 6.5H21v-3.5");
}

</style>
