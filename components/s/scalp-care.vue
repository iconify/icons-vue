<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8zn8-b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scalp-care" /></template>
<style>
.t8zn8-b7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.5v-4C4 15.75 3 13.25 3 10.5C3 6.25 6.25 3 10.5 3c4 0 7 2.75 7 6.75l.923 2.154M13.974 18.5H13.5v3m5.75-6.5s2.5 2.5 2.5 4.25a2.5 2.5 0 0 1-5 0c0-1.75 2.5-4.25 2.5-4.25Z");
}

</style>
