<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcnfc7oqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seedling-tray" /></template>
<style>
.pcnfc7oqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19L20 19H4Zm5 0v-4m0 0c0-2.25-1.25-3.5-3-3.5c0 2.25 1.25 3.5 3 3.5m0 0c0-2.25 1.25-3.5 3-3.5c0 2.25-1.25 3.5-3 3.5m9 4v-4m0 0c0-2.25-1.25-3.5-3-3.5c0 2.25 1.25 3.5 3 3.5m0 0c0-2.25 1.25-3.5 3-3.5c0 2.25-1.25 3.5-3 3.5");
}

</style>
