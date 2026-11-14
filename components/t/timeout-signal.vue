<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3b4-6bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:timeout-signal" /></template>
<style>
.t3b4-6bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v4.5h-19Zm7.25 4.5v10.75a2.25 2.25 0 0 0 4.5 0V8.5m-9.75 0v1a2 2 0 0 0 2 2H7");
}

</style>
