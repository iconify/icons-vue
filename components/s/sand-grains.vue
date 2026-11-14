<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5-egv69v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sand-grains" /></template>
<style>
.f5-egv69v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 6.5a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm-3.5 6a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm7 0a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm-10.5 6a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm7 0a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm7 0a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

</style>
