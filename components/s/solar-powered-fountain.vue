<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gao6bbcwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-powered-fountain" /></template>
<style>
.gao6bbcwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.64 14.611Q9.534 15 8 15q-5.5 0-5.5-5h11q0 .626-.086 1.173M8 15v5.5m-2.5 0h5M8 10V5c0-2.5 4-2.5 4 1.5m4 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5-3.5v-1m0 8v1M14 17.5h-1m8 0h1M20 15l.75-.75M20 20l.75.75M15 20l-.75.75M15 15l-.75-.75");
}

</style>
