<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8k95ocba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-geyser" /></template>
<style>
.j8k95ocba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.5c1.5-3.75 14.5-3.75 16 0Zm8-6v-11m-2.75 11L5.5 6m9.25 8.5L18.5 6m-10-3h.01m6.99 0h.01");
}

</style>
