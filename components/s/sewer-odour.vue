<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz1ndbc9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sewer-odour" /></template>
<style>
.xz1ndbc9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm3-1.5h5m-5 3h5m-7-9.75q-1.25-1.25 0-2.5t0-2.5m4.5 5q-1.25-1.25 0-2.5t0-2.5m4.5 5q-1.25-1.25 0-2.5t0-2.5");
}

</style>
