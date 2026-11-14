<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkzfjjbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wave-particle" /></template>
<style>
.mkzfjjbdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15c1.75-5 4.25-5 6 0s4.25 5 6 0s4.25-5 6 0M15 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
