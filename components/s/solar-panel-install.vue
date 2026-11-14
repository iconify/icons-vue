<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snbwb8b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-panel-install" /></template>
<style>
.snbwb8b2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.83 3h10.868a1.75 1.75 0 0 1 1.686 2.218l-1.528 5.5A1.75 1.75 0 0 1 17.17 12H6.302a1.75 1.75 0 0 1-1.686-2.218l1.528-5.5A1.75 1.75 0 0 1 7.83 3M8 12v8.5m8-8.5v8.5m-12.5 0h17M13.75 3l-2.5 9m-6-4.5h14.5");
}

</style>
