<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z45a16whz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wedge" /></template>
<style>
.z45a16whz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 9.922V16.5a1.5 1.5 0 0 0 1.5 1.5h5.892a1.5 1.5 0 0 0 1.118-2.501l-5.893-6.577a1.5 1.5 0 0 0-2.617 1M3 12h3.5m-2-2l2 2l-2 2");
}

</style>
