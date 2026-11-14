<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h30oudbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:teeth-whitening" /></template>
<style>
.h30oudbom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5C5.25 6.5 4.5 8 4.5 10s1 3.5 1.5 5l.75 4.5c.25 1 1.25 1 1.5 0l.5-2.75a.781.781 0 0 1 1.5 0l.5 2.75c.25 1 1.25 1 1.5 0L13 15c.5-1.5 1.5-3 1.5-5s-.75-3.5-2.5-3.5c-1 0-1.5.75-2.5.75S8 6.5 7 6.5m9.5-4V5M19 7l2.5-2.5m-2.25 5.25h2.5");
}

</style>
