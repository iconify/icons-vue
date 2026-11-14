<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egggzp--u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-bathing" /></template>
<style>
.egggzp--u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19v2a4 4 0 0 1-4 4h-11a4 4 0 0 1-4-4Zm4 6l-1 2m12-2l1 2M6.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM4.5 13c0-2 2-3 4.5-3s4.5 1 4.5 3");
}

</style>
