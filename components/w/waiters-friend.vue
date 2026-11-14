<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5j_ez5bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waiters-friend" /></template>
<style>
.q5j_ez5bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h18v3.5H3Zm9 3.5l1.75 1.5l-3.5 2l3.5 2l-3.5 2L12 20.5M4.75 8l3.5-3.5");
}

</style>
