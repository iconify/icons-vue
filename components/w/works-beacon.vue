<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r167dsbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:works-beacon" /></template>
<style>
.r167dsbkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 15v-4a4.5 4.5 0 0 1 9 0v4m-9 0h9a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 17.5A2.5 2.5 0 0 1 7.5 15M12 2v1.5M4.5 6l1.25 1.25M19.5 6l-1.25 1.25M2.5 11h1.25m16.5 0h1.25");
}

</style>
