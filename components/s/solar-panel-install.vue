<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx73ssbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-panel-install" /></template>
<style>
.qx73ssbmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3H21l-2.5 9H4ZM8 12v8.5m8-8.5v8.5m-12.5 0h17M13.75 3l-2.5 9m-6-4.5h14.5");
}

</style>
