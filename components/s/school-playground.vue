<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p47k9ilqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:school-playground" /></template>
<style>
.p47k9ilqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21V7m4 14V7m-4 4.5h4M4 16h4m0-9c2 0 3 1 4 3l4 8c.75 1.5 2 2.5 4 2.5");
}

</style>
