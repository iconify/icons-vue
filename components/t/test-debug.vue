<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vuaj8bbjq"/><path class="sla96lbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-debug" /></template>
<style>
.sla96lbdg {
  d: path("M6.75 5.75a2.25 2.25 0 0 1 4.5 0M3 8l2.5 1M3 11.5h2.5M3 15l2.5-1m7-5L15 8m-2.5 3.5H15m-2.5 2.25l1.791.179M15.25 18a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM20 20l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vuaj8bbjq {
  d: path("M7 5h4a1.5 1.5 0 0 1 1.5 1.5v7A1.5 1.5 0 0 1 11 15H7a1.5 1.5 0 0 1-1.5-1.5v-7A1.5 1.5 0 0 1 7 5Z");
}

</style>
