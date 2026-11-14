<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no_0o_bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:printer-pause" /></template>
<style>
.no_0o_bmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v10.5h-19Zm4 10.5v5a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-5m-8 3h5M10.5 7v4.5m3-4.5v4.5");
}

</style>
