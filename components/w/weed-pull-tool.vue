<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnlqdjssw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weed-pull-tool" /></template>
<style>
.nnlqdjssw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.525 18.5L7 16.025a1.75 1.75 0 0 1 2.475 0a1.75 1.75 0 0 1 0 2.475L7 20.975a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475M9.5 16l5.5-5.5M17.5 6L15 10.5L19.5 8m-13-1.5v5m0-5c0-2.5-1.75-4-4-4c0 2.5 1.75 4 4 4m0 0c0-2.5 1.75-4 4-4c0 2.5-1.75 4-4 4");
}

</style>
