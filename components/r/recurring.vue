<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdg0nbbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recurring" /></template>
<style>
.fdg0nbbxr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 17.25h-5.5a2.5 2.5 0 0 1-2.5-2.5v-7.5a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v3.5m-18.5-2h18.5m-3.25 6A3.25 3.25 0 1 1 14.75 18m-1.25 1.25L14.75 18L16 19.25");
}

</style>
