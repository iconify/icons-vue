<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_xgxqav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:team-huddle" /></template>
<style>
.eh_xgxqav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7-2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7 2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM2.5 20.5c0-5 4-7.5 9.5-7.5s9.5 2.5 9.5 7.5");
}

</style>
