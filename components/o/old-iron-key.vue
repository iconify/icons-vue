<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfelmzz4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:old-iron-key" /></template>
<style>
.wfelmzz4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.237 9.237l1.526 1.526a1.75 1.75 0 0 1 0 2.474l-1.526 1.526a1.75 1.75 0 0 1-2.474 0l-1.526-1.526a1.75 1.75 0 0 1 0-2.474l1.526-1.526a1.75 1.75 0 0 1 2.474 0M10 12h11m-8.5-2v4m4.5-2v3.5h1.5V14H20v1.5h1V12");
}

</style>
