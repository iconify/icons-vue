<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rwqsdd7rp"/><path class="db2gipbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:out-and-back-trail" /></template>
<style>
.db2gipbug {
  d: path("M10.75 13.5L8.25 16l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rwqsdd7rp {
  d: path("M3.25 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h9.5a4 4 0 0 1 0 8h-8.5");
}

</style>
