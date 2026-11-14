<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0v91cgqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vinegar-cleaner" /></template>
<style>
.o0v91cgqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.3 21.5H3.5V10h10v8.5M6 10V3.5h8.5v3H11V10m-7.5 5h10m2.5 6.5c0-4.75 2.25-6.5 5.75-6.5c0 4-2 6.5-5.75 6.5Zm0 0l2.75-3.25");
}

</style>
