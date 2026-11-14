<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq-z38bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:summit-meeting" /></template>
<style>
.sq-z38bnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h4a2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2h-2l-2 2v-2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Zm11 0h4a2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2v2l-2-2h-2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2ZM4 15h16m-8 0v5.5m-3.5 0h7");
}

</style>
