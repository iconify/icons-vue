<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i77c1wbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:surface-cleaning" /></template>
<style>
.i77c1wbba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 16.5l1.75-7c.25-.75.75-1 1.5-1H20c.75 0 1.25.75 1 1.5l-1.5 6.5Zm-8.5 3h19m-7.5-7h6M6 9c.25 1.75 1 2.5 2.75 2.75C7 12 6.25 12.75 6 14.5c-.25-1.75-1-2.5-2.75-2.75C5 11.5 5.75 10.75 6 9m2.5 7h.01");
}

</style>
