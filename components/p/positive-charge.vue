<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7u80_43a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:positive-charge" /></template>
<style>
.c7u80_43a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5-2.25v4.5M9.75 12h4.5m3.25-5.5l2-2m-13 2l-2-2m13 13l2 2m-13-2l-2 2");
}

</style>
