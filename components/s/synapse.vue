<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryza1ubvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:synapse" /></template>
<style>
.ryza1ubvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5v2C7 5 6 7 6.5 9c.5 1.75 3 2.5 5.5 2.5s5-.75 5.5-2.5C18 7 17 5 14 4.5v-2M5 16c1.5 2 4 3 7 3s5.5-1 7-3m-7 3v2.5M9.5 14h.01m2.49-.25h.01m2.49.25h.01");
}

</style>
