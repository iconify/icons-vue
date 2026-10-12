<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkfbq-bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mashrabiya" /></template>
<style>
.mkfbq-bmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.75h9.5q.75 0 1.22.58l1.31 1.59q.47.58-.28.58H5q-.75 0-.28-.58l1.31-1.59q.47-.58 1.22-.58m-2 2.75h13.5V17a1 1 0 0 1-1 1H6.25a1 1 0 0 1-1-1Zm6.75 0V18m-6.75-6.25h13.5M7.5 18h9q.75 0 .29.59l-1.58 2.07q-.46.59-1.21.59h-4q-.75 0-1.21-.59l-1.58-2.07Q6.75 18 7.5 18");
}

</style>
