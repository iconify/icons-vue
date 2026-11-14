<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdxgtuh-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:route-number-shield" /></template>
<style>
.bdxgtuh-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h16V10c0 5-3.5 8.5-8 11c-4.5-2.5-8-6-8-11Zm0 3.75h16m-8 3v6m-1.75-4.75L12 10.25");
}

</style>
