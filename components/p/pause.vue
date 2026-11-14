<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-95h_b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pause" /></template>
<style>
.y-95h_b8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4zA2.25 2.25 0 0 1 10 6.25v11.5A2.25 2.25 0 0 1 7.75 20a2.25 2.25 0 0 1-2.25-2.25V6.25A2.25 2.25 0 0 1 7.75 4m8.5 0za2.25 2.25 0 0 1 2.25 2.25v11.5A2.25 2.25 0 0 1 16.25 20A2.25 2.25 0 0 1 14 17.75V6.25A2.25 2.25 0 0 1 16.25 4");
}

</style>
