<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glrfv946i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:range-hood" /></template>
<style>
.glrfv946i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 9V2.75M14.75 9V2.75M10.25 9h3.5q1 0 1.73.68l5.04 4.64q.73.68-.27.68H3.75q-1 0-.27-.68l5.04-4.64Q9.25 9 10.25 9M7 18.25l-1 2.5m6-2.5V21m5-2.75l1 2.5");
}

</style>
