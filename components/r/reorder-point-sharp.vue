<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8wypkbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reorder-point-sharp" /></template>
<style>
.r8wypkbkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5.5h7.5v4.75H4zm-1.25 9.25h10v6.5h-10zm0-2.25h18.5m-.5-5.5a3.25 3.25 0 1 1-3.25-3.25l-1.25-1");
}

</style>
