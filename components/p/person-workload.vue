<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebsvnebol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-workload" /></template>
<style>
.ebsvnebol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M5.5 14.5c0-2 2.5-3.75 6.5-3.75s6.5 1.75 6.5 3.75M4.625 17.25h14.75a2.125 2.125 0 0 1 2.125 2.125a2.125 2.125 0 0 1-2.125 2.125H4.625A2.125 2.125 0 0 1 2.5 19.375a2.125 2.125 0 0 1 2.125-2.125m9.375 0v4.25");
}

</style>
