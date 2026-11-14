<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="citkrsbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oil-lamp-bronze" /></template>
<style>
.citkrsbmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15c0-2 2.5-3.5 6.5-3.5c3 0 5 1 7 1.5l3.5.5v3l-3.5.5c-2 .5-4 1.5-7 1.5C5.5 18.5 3 17 3 15Zm6.5 0h.01M19 10.75c-1.4-.85-1.6-2.65 0-5.25c1.6 2.6 1.4 4.4 0 5.25Z");
}

</style>
