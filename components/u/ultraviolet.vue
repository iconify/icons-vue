<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3nr1zmbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ultraviolet" /></template>
<style>
.j3nr1zmbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 6.75V21m3.5-7.25l3 5.5m-10-5.5l-3 5.5m12.25-7.75l3.5 1.75m-15-1.75l-3.5 1.75");
}

</style>
