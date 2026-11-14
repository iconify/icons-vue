<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovpf55i5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:work-life-balance" /></template>
<style>
.ovpf55i5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.379 17.217l.725 1.692A1.5 1.5 0 0 1 12.725 21h-1.45a1.5 1.5 0 0 1-1.379-2.091l.725-1.692a1.5 1.5 0 0 1 2.758 0M2.5 14h19M5 7.5h3A1.5 1.5 0 0 1 9.5 9v1.5A1.5 1.5 0 0 1 8 12H5a1.5 1.5 0 0 1-1.5-1.5V9A1.5 1.5 0 0 1 5 7.5M2.5 14l1-2h6l1 2m4 0c0-4.5 3-7 7-7c0 4-3 7-7 7m0 0L19 9.5");
}

</style>
