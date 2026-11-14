<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx4kchqet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seek-shade" /></template>
<style>
.jx4kchqet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11a9 8 0 0 1 18 0q-3-1.5-6 0q-3-1.5-6 0q-3-1.5-6 0m9-.75V19m-6 1a6 1.5 0 1 0 12 0a6 1.5 0 1 0-12 0");
}

</style>
