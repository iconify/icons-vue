<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sr2w7bboo"/><path class="sern725pt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mood-note" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sern725pt {
  d: path("M15.031 10.25a3.5 3.5 0 0 1-6.062 0M7 15h9.5M7 18h6");
}

.sr2w7bboo {
  d: path("M5.5 3.5h13a2 2 0 0 1 2 2V15L15 20.5H5.5a2 2 0 0 1-2-2v-13a2 2 0 0 1 2-2m4 3.5h.01m4.99 0h.01");
}

</style>
