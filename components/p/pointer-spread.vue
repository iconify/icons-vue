<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epzz_cb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pointer-spread" /></template>
<style>
.epzz_cb9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 10l10.5 4l-4.5 2l-2 4.5Zm0-3V2.5M7.75 4.75L10 2.5l2.25 2.25M7 10H2.5m2.25-2.25L2.5 10l2.25 2.25");
}

</style>
