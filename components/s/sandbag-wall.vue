<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjaqtt48y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sandbag-wall" /></template>
<style>
.bjaqtt48y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12.5H7.5A1.5 1.5 0 0 1 9 14v1.5A1.5 1.5 0 0 1 7.5 17H4.25a1.5 1.5 0 0 1-1.5-1.5V14a1.5 1.5 0 0 1 1.5-1.5Zm6.25 0h3.25a1.5 1.5 0 0 1 1.5 1.5v1.5a1.5 1.5 0 0 1-1.5 1.5H10.5A1.5 1.5 0 0 1 9 15.5V14a1.5 1.5 0 0 1 1.5-1.5Zm6.25 0H20a1.5 1.5 0 0 1 1.5 1.5v1.5A1.5 1.5 0 0 1 20 17h-3.25a1.5 1.5 0 0 1-1.5-1.5V14a1.5 1.5 0 0 1 1.5-1.5ZM7.25 8h3.25A1.5 1.5 0 0 1 12 9.5V11a1.5 1.5 0 0 1-1.5 1.5H7.25a1.5 1.5 0 0 1-1.5-1.5V9.5A1.5 1.5 0 0 1 7.25 8Zm6.25 0h3.25a1.5 1.5 0 0 1 1.5 1.5V11a1.5 1.5 0 0 1-1.5 1.5H13.5A1.5 1.5 0 0 1 12 11V9.5A1.5 1.5 0 0 1 13.5 8Zm-3.25-4.5h3.5a1.5 1.5 0 0 1 1.5 1.5v1.5a1.5 1.5 0 0 1-1.5 1.5h-3.5a1.5 1.5 0 0 1-1.5-1.5V5a1.5 1.5 0 0 1 1.5-1.5ZM3 20.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
