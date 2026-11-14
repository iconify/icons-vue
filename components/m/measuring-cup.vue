<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxd0zlf_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:measuring-cup" /></template>
<style>
.bxd0zlf_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7h12l-1 12c-.2 1-1 1.5-2 1.5H8c-1 0-1.8-.5-2-1.5Zm12 2c3.5 0 3.5 5-.5 5m-10-2h3m-3 4h3");
}

</style>
