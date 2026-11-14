<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp8toqges"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:password-strong" /></template>
<style>
.hp8toqges {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m7-3L20 3m-2.25 2.25l2 2M15 8l2 2m-2.25 8l2 2L21 15.75");
}

</style>
