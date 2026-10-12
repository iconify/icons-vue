<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2ud1hb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:port-scan" /></template>
<style>
.o2ud1hb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.75h14.5q1.25 0 1.25 1.25v4.25q0 1.25-1.25 1.25h-1.5q-1.25 0-1.25 1.25V20q0 1.25-1.25 1.25h-6.5Q7.5 21.25 7.5 20v-2.25q0-1.25-1.25-1.25h-1.5q-1.25 0-1.25-1.25V11q0-1.25 1.25-1.25M8 12.25v2m2.67-2v2m2.66-2v2m2.67-2v2M12 6.5V2.75m-5.25 4.5L5 4.75m12.25 2.5L19 4.75");
}

</style>
