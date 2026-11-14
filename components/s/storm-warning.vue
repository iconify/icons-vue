<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbo78ubbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:storm-warning" /></template>
<style>
.lbo78ubbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11a3 3 0 0 1 0-6a4.25 4.25 0 0 1 8.25.75A2.75 2.75 0 0 1 13 11Zm4.054 3.755l-2.026 2.153A.648.648 0 0 0 8 18a1.13 1.13 0 0 1 1.088 1.442L9 19.75a.421.421 0 0 0 .718.397l2.362-2.625a.612.612 0 0 0-.455-1.022a1.256 1.256 0 0 1-1.251-1.369l.001-.006a.476.476 0 0 0-.821-.37M20 4v10m0 4.25h.01");
}

</style>
