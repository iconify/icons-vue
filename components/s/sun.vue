<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joe186t2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sun" /></template>
<style>
.joe186t2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-9.5v2m0 15v2M2.5 12h2m15 0h2M5.25 5.25l1.5 1.5m10.5 10.5l1.5 1.5m0-13.5l-1.5 1.5m-12 12l1.5-1.5");
}

</style>
