<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxogk-bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-candy" /></template>
<style>
.vxogk-bqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20V8.5a6 6 0 0 1 12 0v2H13v-2a2.5 2.5 0 0 0-5 0V20Zm0-6.5l3.5-2m-3.5 7l3.5-2M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
