<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbwnch6-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vr-headset-cast" /></template>
<style>
.kbwnch6-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13h8a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2a2 2 0 0 0-4 0h-2a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Zm8-10.5h9v7h-9Zm-7 7.5l4-4m-3 0h3v3");
}

</style>
