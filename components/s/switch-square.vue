<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de_9jdbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:switch-square" /></template>
<style>
.de_9jdbly {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 4.75h-8.5q-2.485 0-4.243 1.757Q1.75 8.265 1.75 10.75v2.5q0 2.485 1.757 4.243Q5.265 19.25 7.75 19.25h8.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-2.5q0-2.485-1.757-4.243Q18.735 4.75 16.25 4.75M14.875 8h1.25Q19.5 8 19.5 11.375v1.25q0 1.398-.989 2.386q-.988.989-2.386.989h-1.25q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-1.25Q11.5 8 14.875 8");
}

</style>
