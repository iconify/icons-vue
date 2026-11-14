<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxdtdnbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:turn-signal-left" /></template>
<style>
.mxdtdnbfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.737 10.763l4.349-4.349A.828.828 0 0 1 9.5 7v.25A1.75 1.75 0 0 0 11.25 9h8.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 19.75 15h-8.5a1.75 1.75 0 0 0-1.75 1.75V17a.828.828 0 0 1-1.414.586l-4.349-4.349a1.75 1.75 0 0 1 0-2.474");
}

</style>
