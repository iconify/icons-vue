<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amd6k8bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:unicycle" /></template>
<style>
.amd6k8bta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.75h4.75a1.75 1.75 0 0 1 0 3.5H9.75a1.75 1.75 0 0 1 0-3.5M12 6.25V16.5m-1.5-2.25l3 4.5m-1.5-7a4.75 4.75 0 1 0 0 9.5a4.75 4.75 0 0 0 0-9.5");
}

</style>
