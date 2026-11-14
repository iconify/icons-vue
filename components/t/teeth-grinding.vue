<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnlz3rhkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:teeth-grinding" /></template>
<style>
.fnlz3rhkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5C7.75 5 7 6.5 7 8.5s1 3.5 1.5 5l.75 4.5c.25 1 1.25 1 1.5 0l.5-2.75a.781.781 0 0 1 1.5 0l.5 2.75c.25 1 1.25 1 1.5 0l.75-4.5c.5-1.5 1.5-3 1.5-5S16.25 5 14.5 5c-1 0-1.5.75-2.5.75S10.5 5 9.5 5M4.25 7l-2 2.5l2 2.5l-2 2.5M19.75 7l2 2.5l-2 2.5l2 2.5");
}

</style>
