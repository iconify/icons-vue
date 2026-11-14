<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b603s-zwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouth-guard-sport" /></template>
<style>
.b603s-zwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5C2.5 14 6 19 12 19s9.5-5 9.5-13.5a2.25 2.25 0 0 0-4.5 0c0 6-1.5 9-5 9s-5-3-5-9a2.25 2.25 0 0 0-4.5 0Zm9.5 9V19m-5.25-4L9 12.75M17.25 15L15 12.75");
}

</style>
