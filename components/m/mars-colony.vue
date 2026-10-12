<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3fefcbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mars-colony" /></template>
<style>
.x3fefcbyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.5L7 6.25L10.5 10l3.25-3.5l5.5 5.25l2-1.75M2.75 20.5a5.25 5.25 0 0 1 10.5 0Zm11.5 0a3.5 3.5 0 0 1 7 0ZM8 20.5v-1.75");
}

</style>
