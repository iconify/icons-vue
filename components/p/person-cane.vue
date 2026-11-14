<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxer93bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-cane" /></template>
<style>
.pxer93bpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M9 8v6.5M6.5 21L9 14.5l2.5 6.5M9 9.5l7 3m-3-2a1.5 1.5 0 0 1 3 0V21");
}

</style>
