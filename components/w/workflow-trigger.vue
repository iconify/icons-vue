<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w4dl6r6wm"/><path class="byk5kpsba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:workflow-trigger" /></template>
<style>
.byk5kpsba {
  d: path("m11.688 8.395l-2.192 3.166A.917.917 0 0 0 10.25 13a1.404 1.404 0 0 1 1.37 1.708l-.12.542a.451.451 0 0 0 .812.355l2.192-3.166A.917.917 0 0 0 13.75 11a1.404 1.404 0 0 1-1.37-1.708l.12-.542a.451.451 0 0 0-.812-.355");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4dl6r6wm {
  d: path("M8.25 3h7.5A5.25 5.25 0 0 1 21 8.25v7.5A5.25 5.25 0 0 1 15.75 21h-7.5A5.25 5.25 0 0 1 3 15.75v-7.5A5.25 5.25 0 0 1 8.25 3");
}

</style>
