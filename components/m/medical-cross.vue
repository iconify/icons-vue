<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbnbrguab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-cross" /></template>
<style>
.qbnbrguab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.5h2a1.75 1.75 0 0 1 1.75 1.75V7.5a1.75 1.75 0 0 0 1.75 1.75h2.25A1.75 1.75 0 0 1 20.5 11v2a1.75 1.75 0 0 1-1.75 1.75H16.5a1.75 1.75 0 0 0-1.75 1.75v2.25A1.75 1.75 0 0 1 13 20.5h-2a1.75 1.75 0 0 1-1.75-1.75V16.5a1.75 1.75 0 0 0-1.75-1.75H5.25A1.75 1.75 0 0 1 3.5 13v-2a1.75 1.75 0 0 1 1.75-1.75H7.5A1.75 1.75 0 0 0 9.25 7.5V5.25A1.75 1.75 0 0 1 11 3.5");
}

</style>
