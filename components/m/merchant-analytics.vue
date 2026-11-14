<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de_i9_f1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:merchant-analytics" /></template>
<style>
.de_i9_f1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5L4.5 4h15L21 9.5ZM4.5 12v8h15v-8m-11 6v-3m3.5 3v-4.5m3.5 4.5v-2");
}

</style>
