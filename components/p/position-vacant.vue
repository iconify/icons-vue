<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjs124bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:position-vacant" /></template>
<style>
.wjs124bgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5h4a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 14 8h-4a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 10 2.5M4 14h4a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 8 20.5H4a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 4 14m8-6v3.25M6 14v-2.75h12V14m-1.75 0h3.5m-5.5 2.25v2m7.5-2v2m-5.5 2.25h3.5");
}

</style>
