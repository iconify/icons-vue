<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcikbixnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-passbook-print" /></template>
<style>
.wcikbixnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5V4A1.5 1.5 0 0 1 8 2.5h8A1.5 1.5 0 0 1 17.5 4v5.5m-15 2h19v8h-19Zm3.5 10h12m-8.25-19v7m7.75 6h.01");
}

</style>
