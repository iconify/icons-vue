<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6h2gobbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-lesson" /></template>
<style>
.s6h2gobbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2.5 17.5C2.5 14.5 4 13 6 13s3.5 1.5 3.5 4.5m-7 3H10m4.25-18h5.5a1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-3.5a1.75 1.75 0 0 1 1.75-1.75m-.75 18l1-11m5 0l1 11M8 13.5L12.5 7");
}

</style>
