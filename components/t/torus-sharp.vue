<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyvl_3vil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:torus-sharp" /></template>
<style>
.uyvl_3vil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 6.75 0 1 0 18.5 0a9.25 6.75 0 1 0-18.5 0Zm4.75-.5a4.5 2.5 0 1 1 9 0a4.5 2.5 0 1 1-9 0Z");
}

</style>
