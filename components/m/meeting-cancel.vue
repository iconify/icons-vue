<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf0salbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meeting-cancel" /></template>
<style>
.pf0salbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.1V4.5h12.6M21 6.9v14.6H6.4M3 9.5h7.6m7.8 0H21m-13-7v4m8-4v1.6m4.5-.6l-17 17");
}

</style>
