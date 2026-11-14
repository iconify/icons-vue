<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkheuf62y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swelling" /></template>
<style>
.lkheuf62y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4.5v8c0 2-.75 3.25-.75 4.5s1 2 2.25 2h7.25c1 0 1.5-.75 1.25-1.5s-1.5-1.25-3-1.75l-1.75-1q-.75-.75-.75-2.25v-8M6 6v3m-.25 3c-.5 1.5-.75 3-.5 4.5m1 3c.5 1.25 1.5 2 3 2m2.75 0h3m3 0c2 0 3.5-.75 3.5-2.25m-.75-3c-.75-1.25-2-2-3.25-2.5m-1-4.25v-3");
}

</style>
