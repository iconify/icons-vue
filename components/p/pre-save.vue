<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urpm_8sti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pre-save" /></template>
<style>
.urpm_8sti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 16.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m6 0V3L17 5v3.5l-6.5-2m5.5 8h5V21l-2.5-2l-2.5 2Z");
}

</style>
