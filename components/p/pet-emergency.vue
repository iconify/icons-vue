<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m466-jn8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-emergency" /></template>
<style>
.m466-jn8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.317 19.011c-1.329.954-2.991 1.489-4.817 1.489c-4.5 0-8-3.25-8-8v-10l5 3.5h6l5-3.5v9.493m-11-.493h.01m5.99 0h.01M18 14.75v3.5M18 21h.01");
}

</style>
