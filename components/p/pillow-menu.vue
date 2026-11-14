<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_7mnjsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pillow-menu" /></template>
<style>
.ck_7mnjsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.25c4.25 2 12.25 2 16.5 0c-2 3.25-2 6.25 0 9.5c-4.25-2-12.25-2-16.5 0C5 9.5 5 6.5 3 3.25m12.5 12.5h6m-6 3h6m-6 3h4");
}

</style>
