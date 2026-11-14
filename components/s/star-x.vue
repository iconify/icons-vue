<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a99860j7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:star-x" /></template>
<style>
.a99860j7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.779 5.709l.677 1.455a1.5 1.5 0 0 0 1.178.855l1.592.195a1.135 1.135 0 0 1 .636 1.957l-1.174 1.093a1.5 1.5 0 0 0-.45 1.385l.307 1.574a1.135 1.135 0 0 1-1.664 1.21l-1.403-.779a1.5 1.5 0 0 0-1.456 0l-1.403.779a1.135 1.135 0 0 1-1.664-1.21l.307-1.574a1.5 1.5 0 0 0-.45-1.385l-1.174-1.093a1.135 1.135 0 0 1 .636-1.957l1.592-.195a1.5 1.5 0 0 0 1.178-.855l.677-1.455a1.135 1.135 0 0 1 2.058 0M15.5 15.5l5 5m0-5l-5 5");
}

</style>
