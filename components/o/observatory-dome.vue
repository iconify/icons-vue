<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fja_ibciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:observatory-dome" /></template>
<style>
.fja_ibciy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.25a9 9 0 0 1 7.75-8.91v8.91Zm10.25-8.91A9 9 0 0 1 21 21.25h-7.75ZM12 2.75q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25Q11.61 6.39 8.75 6q2.86-.39 3.25-3.25");
}

</style>
