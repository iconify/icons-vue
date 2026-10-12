<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py5aopbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swab-stick" /></template>
<style>
.py5aopbch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 20.25L14.5 9.5m4.69-4.55l-.14-.14q-1.34-1.34-2.68 0l-1.56 1.56q-1.34 1.34 0 2.68l.14.14q1.34 1.34 2.68 0l1.56-1.56q1.34-1.34 0-2.68");
}

</style>
