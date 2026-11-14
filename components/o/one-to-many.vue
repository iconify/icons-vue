<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7tx4vbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:one-to-many" /></template>
<style>
.p7tx4vbgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-9.5-7H17m-5 0l5.5-5.5M12 12l5.5 5.5");
}

</style>
