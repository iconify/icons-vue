<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc8osbfrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:talk-therapy" /></template>
<style>
.jc8osbfrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h8a2 2 0 0 1 2 2V7a2 2 0 0 1-2 2H8.5l-3 2.5V9H5a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2Zm7 9.5h7a2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2h-.5V21l-3-2.5H12a2 2 0 0 1-2-2V14a2 2 0 0 1 2-2Z");
}

</style>
