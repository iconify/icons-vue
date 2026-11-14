<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc5d-ib8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swim-between-flags" /></template>
<style>
.tc5d-ib8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 16.25V3h4v4.5H6m12 8.75V3h-4v4.5h4M3 20q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
