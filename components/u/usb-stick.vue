<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jbxdxib5c"/><path class="jptl3qwem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:usb-stick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbxdxib5c {
  d: path("M10 2.5h4A1.5 1.5 0 0 1 15.5 4v1.5A1.5 1.5 0 0 1 14 7h-4a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 10 2.5M11 7h2a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 7.5 18v-7.5A3.5 3.5 0 0 1 11 7m-.25-2.25h.01m2.49 0h.01");
}

.jptl3qwem {
  d: path("M10.5 17.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
