<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikrhklacw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reward-streak" /></template>
<style>
.ikrhklacw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75S6 8.5 6 14a6 6 0 0 0 12 0c0-2.5-1.5-4.5-2.5-5.5c0 2-1.5 2.5-2 2.5c0-3-1.5-8.25-1.5-8.25Z");
}

</style>
