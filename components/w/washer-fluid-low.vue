<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbyx41b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:washer-fluid-low" /></template>
<style>
.sbyx41b2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7c5-2 12-2 17 0l-2 9.5c-4.5-1-8.5-1-13 0Zm8.5 6v7.5m-4-9h.01M10 9.75h.01m3.99 0h.01M16 11.5h.01");
}

</style>
