<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up49o2bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medication-reminder" /></template>
<style>
.up49o2bij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.4 19.5H5V6h9v7.3M4 2.5h11V6H4Zm3.5 8h4m3.75 9.5v-2.75c0-1.65 1.25-3 2.75-3s2.75 1.35 2.75 3V20Zm-1 0h7.5m-4.5 1.75h1.5");
}

</style>
