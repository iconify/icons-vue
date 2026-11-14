<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhp2auexv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:syrup-bottle" /></template>
<style>
.yhp2auexv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6V3.5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1V6Zm.5 0v1.5Q6 8.75 6 11.5V20a1.5 1.5 0 0 0 1.5 1.5h9A1.5 1.5 0 0 0 18 20v-8.5q0-2.75-3.5-4V6M6 14.5h12");
}

</style>
