<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp35-lb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-users" /></template>
<style>
.dp35-lb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.372 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.276 0 2.462.203 3.497.575M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm12 6.75l-3.75 4.25H18l-1 3.25l3.75-4.5H18Z");
}

</style>
