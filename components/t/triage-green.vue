<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eeelanbur"/><path class="vxfyfebqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:triage-green" /></template>
<style>
.eeelanbur {
  d: path("m12 4l5.5 4v11.5c0 1.1-.9 2-2 2h-7c-1.1 0-2-.9-2-2V8Zm0 4l4-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxfyfebqw {
  d: path("M10.75 8a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M10 12.25c.5-.5 1.25-.75 2-.75c1.1 0 2 .65 2 1.75c0 .9-.9 1.5-2 1.5c1.25 0 2.25.75 2.25 1.75c0 1.2-1 2-2.25 2c-.9 0-1.6-.35-2.25-.75");
}

</style>
