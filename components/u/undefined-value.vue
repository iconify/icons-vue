<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-o2ybc2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:undefined-value" /></template>
<style>
.s-o2ybc2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5h-3v17h3m9-17h3v17h-3m-7-11a2.5 2.5 0 1 1 3.75 2.25c-.85.4-1.25 1-1.25 1.75m0 3h.01");
}

</style>
