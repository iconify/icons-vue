<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt2g8ubuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-layer-boundaries" /></template>
<style>
.nt2g8ubuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12L3 8l3-1.75m2.5-1.5l3-1.75l3.25 1.5m3 1L21 7l-1 5m-.5 3l-1 5l-5.25-.5m-3 0L5 19l-.75-4");
}

</style>
