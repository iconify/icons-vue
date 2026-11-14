<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1j99abgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robotics-kit" /></template>
<style>
.i1j99abgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 8h3.5A5.25 5.25 0 0 1 19 13.25v.5A5.25 5.25 0 0 1 13.75 19h-3.5A5.25 5.25 0 0 1 5 13.75v-.5A5.25 5.25 0 0 1 10.25 8M12 3v5m-1-5a1 1 0 1 0 2 0a1 1 0 1 0-2 0M9 13h.01M15 13h.01M3 12v3m18-3v3");
}

</style>
