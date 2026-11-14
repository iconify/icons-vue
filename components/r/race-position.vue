<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9i913b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:race-position" /></template>
<style>
.u9i913b_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5v-7h6V11h7v5.5h6v5ZM12 11V3m1.5 0h1.75a.625.625 0 0 1 .5 1l-.075.1a1.5 1.5 0 0 0 0 1.8l.075.1a.625.625 0 0 1-.5 1H13.5A1.5 1.5 0 0 1 12 5.5v-1A1.5 1.5 0 0 1 13.5 3");
}

</style>
