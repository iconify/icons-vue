<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayxtt1psy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:speed-skate" /></template>
<style>
.ayxtt1psy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4.5H10V10l4 1.5a2.5 2.5 0 0 1 2 2.5v1.5H5.5ZM2.5 19H19q2.5 0 2.5-2.5m-14-1V19m6-3.5V19");
}

</style>
