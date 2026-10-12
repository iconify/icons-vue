<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix3wk2bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-fastener-sharp" /></template>
<style>
.ix3wk2bpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.75a5.5 5 0 0 1 11 0Zm4 0v5L7.25 21M13.5 9.75v5L16.75 21m-14-7.75h18.5");
}

</style>
