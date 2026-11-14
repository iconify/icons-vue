<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twejvabwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warning-sign-blank" /></template>
<style>
.twejvabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.307 7.25l5.088 9.373a2.625 2.625 0 0 1-2.307 3.877H6.912a2.625 2.625 0 0 1-2.307-3.877L9.693 7.25a2.625 2.625 0 0 1 4.614 0");
}

</style>
