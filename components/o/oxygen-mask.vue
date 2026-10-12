<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpz4t0bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oxygen-mask" /></template>
<style>
.vpz4t0bxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 9h-4m14.5 0h4M12 3.25zq2.25 0 3.01 2.12l2.23 6.26q.76 2.12-1.49 2.12h-7.5q-2.25 0-1.49-2.12l2.23-6.26Q9.75 3.25 12 3.25m-1.5 7h.01m2.99 0h.01M12 13.75v2.5c0 2 1.25 3.25 3.25 3.25h6");
}

</style>
