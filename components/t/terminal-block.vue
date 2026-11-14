<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5qtjtb1u"/><path class="u1_62nbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:terminal-block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5qtjtb1u {
  d: path("M4.75 5h14.5A1.75 1.75 0 0 1 21 6.75v6.5A1.75 1.75 0 0 1 19.25 15H4.75A1.75 1.75 0 0 1 3 13.25v-6.5A1.75 1.75 0 0 1 4.75 5M7 15v4m5-4v4m5-4v4");
}

.u1_62nbnz {
  d: path("M5.25 10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
