<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z60y_cc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swamp" /></template>
<style>
.z60y_cc5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15V4.5m0 4L9.25 5.75M12 10.5l3-3m-7.25 10C9 16 10.25 15 12 15s3 1 4.25 2.5m-13.5 0h2.5m13.5 0h2.5m-18.5 3.75c1.54 0 1.54-1.25 3.08-1.25s1.54 1.25 3.08 1.25S10.45 20 11.99 20s1.54 1.25 3.08 1.25S16.61 20 18.15 20s1.54 1.25 3.08 1.25");
}

</style>
