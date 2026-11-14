<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8l0wcbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neap-tide" /></template>
<style>
.a8l0wcbdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 3.5a5 5 0 1 0 0 8a5 5 0 0 1 0-8ZM3 17q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0M3 20.5q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
