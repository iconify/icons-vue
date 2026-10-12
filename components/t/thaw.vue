<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq6lm7bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thaw" /></template>
<style>
.gq6lm7bqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.25v9.5m4.11-7.12l-8.22 4.75m8.22 0L3.89 5.63m12.08 2.76l-3.48 6.63a4.25 4.25 0 1 0 7.52 0l-3.48-6.63q-.28-.53-.56 0");
}

</style>
