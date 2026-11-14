<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4riahb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rooster-weathervane" /></template>
<style>
.v4riahb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3c0 4 2 7 5 7h3.5c2 0 2.5-2 1.5-3.5l-.5-2L18 4l-2-1.5c-1 0-1.5 1-1.5 2.5L14 7c-2 0-4.5-1.5-7-4Zm5 7v11.5m-8-6h16M17.5 13l2.5 2.5l-2.5 2.5M4 13l2.5 2.5L4 18");
}

</style>
