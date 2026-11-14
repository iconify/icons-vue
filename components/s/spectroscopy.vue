<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4f0qyb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spectroscopy" /></template>
<style>
.s4f0qyb5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.435 8.63l-3.669 7.337A1.75 1.75 0 0 0 8.332 18.5h7.336a1.75 1.75 0 0 0 1.566-2.533L13.565 8.63a1.75 1.75 0 0 0-3.13 0M2.5 15.5l6-3m7 0l6-3m-6 3l6 1.5m-6-1.5l6 6");
}

</style>
