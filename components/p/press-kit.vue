<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzujtdb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:press-kit" /></template>
<style>
.bzujtdb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9V3.5h11V9M2.5 9H9l1.5 2h11v8.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2ZM9 6.25h5");
}

</style>
