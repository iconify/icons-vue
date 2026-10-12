<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2op32jpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pushpin" /></template>
<style>
.e2op32jpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.09 7.49l1.42 1.42q.53.53 0 1.06l-2.12 2.12q-.53.53-.53 1.28v3.09q0 .75-.53.22l-6.01-6.01q-.53-.53.22-.53h3.09q.75 0 1.28-.53l2.12-2.12q.53-.53 1.06 0m.08-3.26l4.6 4.6m-9.45 4.85l-6.01 6.01");
}

</style>
