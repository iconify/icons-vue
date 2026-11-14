<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqf9k9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weightlessness" /></template>
<style>
.oqf9k9bvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM4 20.5h16m-15.5-10V15m15-4.5V15");
}

</style>
