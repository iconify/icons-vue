<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p07medchi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mammal" /></template>
<style>
.p07medchi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c-3 0-6 3.5-6 6c0 2 1.5 3 3 3s2-.75 3-.75s1.5.75 3 .75s3-1 3-3c0-2.5-3-6-6-6m-9.75-1.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0M7 5a1.75 2.5 0 1 0 3.5 0A1.75 2.5 0 1 0 7 5m6.5 0A1.75 2.5 0 1 0 17 5a1.75 2.5 0 1 0-3.5 0m4.75 5.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0");
}

</style>
