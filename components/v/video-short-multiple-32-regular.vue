<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tjmzgrltx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-32-regular" /></template>
<style>
.tjmzgrltx {
  fill: currentColor;
  d: path("M25.993 6.254A4.5 4.5 0 0 1 28 10v12a8 8 0 0 1-8 8h-8a4.5 4.5 0 0 1-3.746-2.007Q8.377 28 8.5 28H20a6 6 0 0 0 6-6V6.5q0-.123-.007-.246M20 2a4.5 4.5 0 0 1 4.5 4.5V22a4.5 4.5 0 0 1-4.5 4.5H8.5A4.5 4.5 0 0 1 4 22V6.5A4.5 4.5 0 0 1 8.5 2zM8.5 4A2.5 2.5 0 0 0 6 6.5V22a2.5 2.5 0 0 0 2.5 2.5H20a2.5 2.5 0 0 0 2.5-2.5V6.5A2.5 2.5 0 0 0 20 4zm2.5 7.751c0-1.57 1.727-2.528 3.06-1.696l4 2.499a2 2 0 0 1 0 3.392l-4 2.5c-1.332.831-3.06-.126-3.06-1.696z");
}

</style>
