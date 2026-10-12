<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t40jvtbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sushi" /></template>
<style>
.t40jvtbnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.07 11.32v-.57Q3.09 9 4.75 8.44L9.34 6.9q1.66-.56 3.41-.6l4.84-.12q1.75-.04 2.37 1.6l.2.52q.62 1.64-1.1 1.94L4.77 12.77q-1.72.3-1.7-1.45m3.08-1.69l1.56 1.96m2.78-3.23l1.57 1.95m2.95-2.24l1.57 1.96m-8.37 4.92l8.36-1.47q2.71-.48 3.52 2.15l.16.52q.81 2.63-1.9 3.11l-9.84 1.73q-2.71.48-2.85-2.27l-.02-.54q-.14-2.75 2.57-3.23");
}

</style>
