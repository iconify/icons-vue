<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s0y-4fb7w"/><path class="hv37tacse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:organic-badge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv37tacse {
  d: path("M8.5 15.5c0-4.5 2.5-7 7-7c0 4.5-2.5 7-7 7m0 0l4-4");
}

.s0y-4fb7w {
  d: path("M20 12a3.25 3.25 0 0 1-2.25 5.75A3.25 3.25 0 0 1 12 20a3.25 3.25 0 0 1-5.75-2.25A3.25 3.25 0 0 1 4 12a3.25 3.25 0 0 1 2.25-5.75A3.25 3.25 0 0 1 12 4a3.25 3.25 0 0 1 5.75 2.25A3.25 3.25 0 0 1 20 12");
}

</style>
