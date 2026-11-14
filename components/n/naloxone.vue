<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv0n09bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:naloxone" /></template>
<style>
.qv0n09bsx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12h6v9.5H9Zm-3-2h12v2H6Zm4.75 0l.5-7c.1-.75 1.4-.75 1.5 0l.5 7m-2.75 6h3");
}

</style>
