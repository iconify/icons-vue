<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_agwvbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:users-x" /></template>
<style>
.r_agwvbtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c1.25 0 2.35.25 3.25.75v5.25ZM5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM16 4.5a3.5 3.5 0 0 1 .906 6.881M15.5 15.5l5 5m0-5l-5 5");
}

</style>
