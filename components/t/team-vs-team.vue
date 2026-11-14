<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq2qpggwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:team-vs-team" /></template>
<style>
.qq2qpggwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 6l4 1.5v4c0 3-1.75 5.25-4 6.5c-2.25-1.25-4-3.5-4-6.5v-4Zm11 0l4 1.5v4c0 3-1.75 5.25-4 6.5c-2.25-1.25-4-3.5-4-6.5v-4Zm-11 3.75v4.5m11-2.75h.01");
}

</style>
