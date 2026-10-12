<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsd--ujcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:massage-hands" /></template>
<style>
.hsd--ujcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12V5.75a1.25 1.25 0 0 1 2.5 0V11m0-.5V4.25a1.25 1.25 0 0 1 2.5 0v6.25m0 0V5a1.25 1.25 0 0 1 2.5 0v5.5m0 .5V7A1.25 1.25 0 0 1 18 7v5.25c0 3.3-2.45 5.5-5.5 5.5h-1c-1.9 0-3.1-.8-4.1-2.1L5.1 12.5A1.3 1.3 0 0 1 7.2 11l.8 1m-5 9.25c3-.9 6-1.15 9-1.15s6 .25 9 1.15M20.25 5.5c.9.9.9 2.6 0 3.5");
}

</style>
