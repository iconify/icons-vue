<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh_beybfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sea-waves" /></template>
<style>
.uh_beybfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8q2.25-2 4.5 0T12 8t4.5 0T21 8M3 13q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0M3 18q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
