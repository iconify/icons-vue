<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uacrm-_ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sea-waves" /></template>
<style>
.uacrm-_ln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8q2.25-2 4.5 0T12 8t4.5 0T21 8M3 13q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0M3 18q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
