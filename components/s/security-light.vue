<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo1bqmg5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-light" /></template>
<style>
.lo1bqmg5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v8m5.75-.5a5 5 0 0 1 8.5-5ZM3 8h5.25M10 14l-1.25 6.5m5.75-8L17 19m1.5-9.5l3 5");
}

</style>
