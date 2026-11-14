<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kisklr87z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smoke-detector-ceiling" /></template>
<style>
.kisklr87z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M5.5 4a6.5 6 0 0 0 13 0M12 7h.01m5.24 6.093a10.5 10.5 0 0 1-10.5 0M19.5 16.99a15 15 0 0 1-15 0");
}

</style>
