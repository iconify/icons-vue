<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv7mxbcvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sparkles-celebrate" /></template>
<style>
.xv7mxbcvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4q.75 7.25 8 8q-7.25.75-8 8q-.75-7.25-8-8q7.25-.75 8-8Zm7-1.5q.25 2.25 2.5 2.5q-2.25.25-2.5 2.5q-.25-2.25-2.5-2.5q2.25-.25 2.5-2.5Zm-14 14q.25 2.25 2.5 2.5q-2.25.25-2.5 2.5q-.25-2.25-2.5-2.5q2.25-.25 2.5-2.5Z");
}

</style>
