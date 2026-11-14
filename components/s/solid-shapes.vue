<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5c27lcue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solid-shapes" /></template>
<style>
.l5c27lcue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12.5h4.5A1.75 1.75 0 0 1 11 14.25v4.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 3 18.75v-4.5a1.75 1.75 0 0 1 1.75-1.75m8.25 4a4 4 0 1 0 8 0a4 4 0 1 0-8 0m.248-11.128l2.197 3.296A1.5 1.5 0 0 1 14.197 11H9.803a1.5 1.5 0 0 1-1.248-2.332l2.197-3.296a1.5 1.5 0 0 1 2.496 0");
}

</style>
