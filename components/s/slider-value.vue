<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw34nyv4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:slider-value" /></template>
<style>
.fw34nyv4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3h5.5a1.75 1.75 0 0 1 1.75 1.75V8.5A1.5 1.5 0 0 1 15 10h-.625a1.75 1.75 0 0 0-1.4.7l-.225.3a.937.937 0 0 1-1.5 0l-.225-.3a1.75 1.75 0 0 0-1.4-.7H9a1.5 1.5 0 0 1-1.5-1.5V4.75A1.75 1.75 0 0 1 9.25 3m.25 15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M3 18h6.5m5 0H21");
}

</style>
