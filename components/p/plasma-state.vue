<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ea2mbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plasma-state" /></template>
<style>
.c5ea2mbwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 3.5L9 12h6l-4 8.5m-8-14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm16-11h.01m-.01 11h.01");
}

</style>
