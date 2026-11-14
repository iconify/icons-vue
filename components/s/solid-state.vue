<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqa1z8bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solid-state" /></template>
<style>
.qqa1z8bvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-14 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-14 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
