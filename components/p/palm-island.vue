<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htf8_wbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:palm-island" /></template>
<style>
.htf8_wbhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20c0-3 4-5 8-5s8 2 8 5Zm8-5c0-3 1-6 1-9m0 0c-3-1-5 0-6.5 2M13 6c3-1 5 0 6.5 2M13 6c-1-2.5-3-3-4.5-2.5");
}

</style>
