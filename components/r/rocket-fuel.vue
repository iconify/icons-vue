<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3409q--i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rocket-fuel" /></template>
<style>
.e3409q--i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5c2.75 2 3.5 5.5 3.5 9V17H6v-5.5c0-3.5.75-7 3.5-9ZM6 12l-2.5 2.5V18L6 17m7-5l2.051 2.051M9.5 9h.01m8.99 5.5s3 2.75 3 4.25a3 3 0 0 1-6 0c0-1.5 3-4.25 3-4.25Z");
}

</style>
