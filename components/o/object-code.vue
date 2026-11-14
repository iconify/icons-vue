<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shaky8bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:object-code" /></template>
<style>
.shaky8bci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5h-1a2 2 0 0 0-2 2v4A2.5 2.5 0 0 1 3 12a2.5 2.5 0 0 1 2.5 2.5v4a2 2 0 0 0 2 2h1m7-17h1a2 2 0 0 1 2 2v4A2.5 2.5 0 0 0 21 12a2.5 2.5 0 0 0-2.5 2.5v4a2 2 0 0 1-2 2h-1M12 12h.01");
}

</style>
