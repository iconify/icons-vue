<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0pixebuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:medal-24-regular" /></template>
<style>
.l0pixebuc {
  fill: currentColor;
  d: path("M17.049 2c.987 0 1.92.449 2.537 1.22l.702.878a3.25 3.25 0 0 1 .166 3.83l-4.25 6.367a5 5 0 1 1-8.41 0L3.55 7.929a3.25 3.25 0 0 1 .164-3.831l.7-.876A3.25 3.25 0 0 1 6.953 2zM12 13.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7M6.014 3.774a1.8 1.8 0 0 0-.428.384l-.7.876a1.75 1.75 0 0 0-.088 2.063l4.026 6.04a5 5 0 0 1 2.173-1.037L6.336 5.107a2 2 0 0 1-.322-1.333M17.997 4c0 .395-.117.78-.336 1.108L13 12.1a5 5 0 0 1 2.174 1.037l4.032-6.041a1.75 1.75 0 0 0-.089-2.062l-.702-.877a1.8 1.8 0 0 0-.433-.386q.014.112.015.228M9.733 7.5l2.265 3.398L14.264 7.5zM8 3.5a.5.5 0 0 0-.415.775L8.734 6h6.529l1.15-1.725a.498.498 0 0 0-.415-.775z");
}

</style>
