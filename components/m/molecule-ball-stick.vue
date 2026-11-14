<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9n_1nphy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:molecule-ball-stick" /></template>
<style>
.f9n_1nphy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6.5-7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6.5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-8-2.25l2.5-2.5m4 0l2.5 2.5");
}

</style>
