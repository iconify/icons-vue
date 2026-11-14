<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj12e8k6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:network-off" /></template>
<style>
.rj12e8k6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.832 13.745q.162.282.39.513t.508.395M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-7.5 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9.5-12v1.6m-5.75 9.15l3.75-3M3.5 3.5l17 17");
}

</style>
