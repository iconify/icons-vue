<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ako8y4e0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tunnel-round" /></template>
<style>
.ako8y4e0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 19v-7a9 9 0 0 1 18 0v7a2 2 0 1 1-4 0v-7a5 5 0 0 0-10 0v7a2 2 0 1 1-4 0M8 8L6 6m6-3v4m4 1l2-2M3 11h4m10 0h4M3 16h4m10 0h4");
}

</style>
