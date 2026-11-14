<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va_vo2hwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pill-percent" /></template>
<style>
.va_vo2hwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.697 10.707l6.01-6.01a3.25 3.25 0 0 1 4.596 0a3.25 3.25 0 0 1 0 4.596l-6.01 6.01a3.25 3.25 0 0 1-4.596 0a3.25 3.25 0 0 1 0-4.596m3.005-3.005l4.596 4.596m2.452 8.952l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
