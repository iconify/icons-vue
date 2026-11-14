<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx4gzbbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thumbs-up" /></template>
<style>
.dx4gzbbum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 11l3.5-6.5c1-1.5 3.5-1 3.25 1.25l-.5 3.75h5.25a2 2 0 0 1 2 2.25l-1.25 6.5a2 2 0 0 1-2 1.75H7Zm-3-.5zA1.5 1.5 0 0 1 5.5 12v6.5A1.5 1.5 0 0 1 4 20a1.5 1.5 0 0 1-1.5-1.5V12A1.5 1.5 0 0 1 4 10.5");
}

</style>
