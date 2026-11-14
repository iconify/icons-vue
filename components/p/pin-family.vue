<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv6zmpaup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-family" /></template>
<style>
.nv6zmpaup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-12.5 15V16A4.5 4.5 0 0 1 7 11.5m14.5 9V16a4.5 4.5 0 0 0-4.5-4.5m-7-.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.5 9.5v-1a3.5 3.5 0 0 1 7 0v1");
}

</style>
