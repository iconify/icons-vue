<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayjrqbbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spatula-lab" /></template>
<style>
.ayjrqbbry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.282 16.596l1.061-1.06a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121l-1.06 1.061a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122m3.182-1.06l4.243-4.243m0-3.536l2.475-2.475a2.5 2.5 0 0 1 3.536 0a2.5 2.5 0 0 1 0 3.536l-2.475 2.475a2.5 2.5 0 0 1-3.536 0a2.5 2.5 0 0 1 0-3.536");
}

</style>
