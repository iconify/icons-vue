<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1xd00byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:upscale-ai-sharp" /></template>
<style>
.u1xd00byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h8v8h-8zm4 0v8m-4-4h8M10 2.75h11.25V14m-8.5-2.75l5.5-5.5m-4.5 0h4.5v4.5");
}

</style>
