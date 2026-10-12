<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3kfef7xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:playground" /></template>
<style>
.i3kfef7xf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.25 12.95l3.25 7.25q.25.55-.35.55h-6.3q-.6 0-.35-.55l3.25-7.25q.25-.55.5 0m-9 2.55l17.5-6.25M5.5 14.7v-3.5m13-1.15v-3.5");
}

</style>
