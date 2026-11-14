<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8r6bpbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mood-scale" /></template>
<style>
.v8r6bpbjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5h6m6 0h6m-12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-6 7h.01m4.49 0h.01m4.49 0h.01m4.49 0h.01m4.49 0h.01");
}

</style>
