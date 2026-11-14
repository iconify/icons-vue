<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzr1dpb5e"/><path class="hagcsdbbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:military-id" /></template>
<style>
.bzr1dpb5e {
  d: path("M6.875 4h10.25A4.375 4.375 0 0 1 21.5 8.375v7.25A4.375 4.375 0 0 1 17.125 20H6.875A4.375 4.375 0 0 1 2.5 15.625v-7.25A4.375 4.375 0 0 1 6.875 4");
}

.hagcsdbbz {
  d: path("M7.323 7.055za1.38 1.38 0 0 0 1.189.864a.348.348 0 0 1 .2.615a1.38 1.38 0 0 0-.454 1.397a.348.348 0 0 1-.523.38a1.38 1.38 0 0 0-1.47 0a.348.348 0 0 1-.523-.38a1.38 1.38 0 0 0-.454-1.397a.348.348 0 0 1 .2-.615a1.38 1.38 0 0 0 1.189-.864a.348.348 0 0 1 .646 0M5 15.5h4.5m3.5-4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M11.25 20c0-3 2-4 4.25-4s4.25 1 4.25 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
