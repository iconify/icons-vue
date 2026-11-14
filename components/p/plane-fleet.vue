<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqc6osb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plane-fleet" /></template>
<style>
.lqc6osb5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c.75 0 1 .75 1 1.5v2l2.25 2.25V10L13 9v2l1 1v.5h-4V12l1-1V9l-2.25 1V8.75L11 6.5v-2c0-.75.25-1.5 1-1.5Zm-6.5 7.5c.75 0 1 .75 1 1.5v2l2.25 2.25v1.25l-2.25-1v2l1 1v.5h-4v-.5l1-1v-2l-2.25 1v-1.25L4.5 14v-2c0-.75.25-1.5 1-1.5Zm13 0c.75 0 1 .75 1 1.5v2l2.25 2.25v1.25l-2.25-1v2l1 1v.5h-4v-.5l1-1v-2l-2.25 1v-1.25L17.5 14v-2c0-.75.25-1.5 1-1.5Z");
}

</style>
