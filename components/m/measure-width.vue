<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn-fo6oin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:measure-width" /></template>
<style>
.jn-fo6oin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19v7h-19ZM7 13v3m5-3v4m5-4v3M3 7h18M5.5 4.5L3 7l2.5 2.5m13-5L21 7l-2.5 2.5");
}

</style>
