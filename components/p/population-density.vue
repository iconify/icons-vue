<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwwfdbc1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:population-density" /></template>
<style>
.rwwfdbc1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.526 4.158L8.06 2.647a1.5 1.5 0 0 1 .886-.02l6.108 1.746a1.5 1.5 0 0 0 .886-.02l3.586-1.195A1.5 1.5 0 0 1 21.5 4.581v13.838a1.5 1.5 0 0 1-1.026 1.423l-4.534 1.511a1.5 1.5 0 0 1-.886.02l-6.108-1.746a1.5 1.5 0 0 0-.886.02l-3.586 1.195A1.5 1.5 0 0 1 2.5 19.419V5.581a1.5 1.5 0 0 1 1.026-1.423M6 7.5h.01M9 7.5h.01M6 10.5h.01m2.99 0h.01m-1.51 3h.01M14.5 12h.01m3.24 4.75h.01");
}

</style>
