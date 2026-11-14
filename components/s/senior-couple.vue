<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw0y8tnzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:senior-couple" /></template>
<style>
.bw0y8tnzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 9a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM6.5 21.5c0-3.75 2.25-6.25 5-6.25s5 2.5 5 6.25M15.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm1 6.25c.5-.35 1-.5 1.5-.5c2.25 0 3.75 1.75 3.75 4.25v3M3 21.5v-12a1.5 1.5 0 0 1 3 0");
}

</style>
