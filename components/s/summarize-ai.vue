<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lec962bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:summarize-ai" /></template>
<style>
.lec962bhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.75h17.5M3.25 8h17.5m-17.5 4.25h17.5m-12 3L12 18l3.25-2.75m-7 5.75h7.5");
}

</style>
