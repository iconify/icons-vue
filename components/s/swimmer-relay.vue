<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5nt7ibtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swimmer-relay" /></template>
<style>
.e5nt7ibtk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-6 5.25h6M2.5 17.5q2.5-2 5 0t5 0t5 0t4 .5");
}

</style>
