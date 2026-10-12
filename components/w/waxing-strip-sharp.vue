<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu7t2xo_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waxing-strip-sharp" /></template>
<style>
.xu7t2xo_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h12v9h-12zm3 2.75l.75 3.25M8.75 8.5l.75 3.25m2.25-3.25l.75 3.25m5.25-4.5h3.5v6h-3.5zm-15 12c3-1.25 6.15-1.25 9.25 0s6.25 1.25 9.25 0");
}

</style>
