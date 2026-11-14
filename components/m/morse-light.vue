<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgp35rb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:morse-light" /></template>
<style>
.wgp35rb4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6.5h7V5h2v11h-2v-1.5H4A1.5 1.5 0 0 1 2.5 13V8A1.5 1.5 0 0 1 4 6.5Zm2.5 8v5m9.25-9h.01m2.74 0h3");
}

</style>
