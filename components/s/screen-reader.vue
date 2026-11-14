<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0wxx8brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:screen-reader" /></template>
<style>
.x0wxx8brf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.5h8M3 10h6m-6 4.5h8M3 19h5m7.828-9.828a4 4 0 0 1 0 5.656M18.48 6.52a7.75 7.75 0 0 1 0 10.96");
}

</style>
