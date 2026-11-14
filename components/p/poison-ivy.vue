<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-zj4fbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:poison-ivy" /></template>
<style>
.f-zj4fbkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21.5v-11m0 0c-2.25-2-2.25-5.5 0-8c2.25 2.5 2.25 6 0 8M9 14c-2 1.5-5.5.5-6.5-3c3-1 5.75.5 6.5 3m7.539-1.077c.41-.524.744-1.165.961-1.923c-3-1-5.75.5-6.5 3a3.45 3.45 0 0 0 1.875.669m2.625.831l5 5m0-5l-5 5");
}

</style>
