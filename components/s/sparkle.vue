<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifyhx9bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sparkle" /></template>
<style>
.ifyhx9bjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c.5 5.75 2.75 8.75 7.5 9.5c-4.75.75-7 3.75-7.5 9.5c-.5-5.75-2.75-8.75-7.5-9.5c4.75-.75 7-3.75 7.5-9.5");
}

</style>
