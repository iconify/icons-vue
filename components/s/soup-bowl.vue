<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn9ignbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soup-bowl" /></template>
<style>
.hn9ignbar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18c0 5.25-4 9-9 9s-9-3.75-9-9Zm6.5-2.75c-1-1 1-2.5 0-4m5 4c-1-1 1-2.5 0-4");
}

</style>
