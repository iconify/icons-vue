<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv5e-6bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shape-subtract" /></template>
<style>
.bv5e-6bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h8.5a2 2 0 0 1 2 2v4h-4.5a2 2 0 0 0-2 2v4.5h-4a2 2 0 0 1-2-2v-8.5a2 2 0 0 1 2-2m13.62 6h.01m2.67 1.16h.01m.19 3.09h.01m-.01 3.12h.01m-.01 3.13h.01m-2.01 2h.01m-3.14 0h.01m-3.13 0h.01m-3.1-.2h.01m-1.17-2.68h.01");
}

</style>
