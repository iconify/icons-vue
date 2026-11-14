<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvbb8vbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vaccination-schedule" /></template>
<style>
.fvbb8vbbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.6 20.5H3.5V5h17v6.7m0 8.5v.3h-.3M8 3v4m8-4v4M3.5 10h15.1m.2 0h1.7m-13 3.5h.01m3.74 0h.01M7.5 17.25h.01m11.551-3.078l1.767 1.767l-3.889 3.889l-1.767-1.767Zm-3.006 4.773l-1.591 1.591m4.243-6.718l2.475 2.475");
}

</style>
