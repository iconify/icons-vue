<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn3jwwb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:network-error" /></template>
<style>
.dn3jwwb7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 12.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m.5-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7.5 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9.5-12V10m-5.75 7.25l3.75-3m9-.75v4m0 3h.01");
}

</style>
