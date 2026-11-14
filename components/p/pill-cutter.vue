<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odwy_ltdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-cutter" /></template>
<style>
.odwy_ltdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5.25a6.75 6.75 0 0 0 0 13.5Zm5.5 0a6.75 6.75 0 0 1 0 13.5ZM12 2.5v19");
}

</style>
