<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezapt8btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tissue-paper" /></template>
<style>
.ezapt8btp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.498 17.176a5.5 5.5 0 0 0-.998.324c-1.75 1.5-3.5-1.5-7 0c-1.5-1.75 1.5-3.5 0-7C2 8.75 5 7 3.5 3.5C5.25 2 7 5 10.5 3.5c1.75-1.5 3.5 1.5 7 0c1.5 1.75-1.5 3.5 0 7c.751.877.374 1.753-.002 2.85M18 17.5c-1.5-2.25-3.75-2.25-3.75-.75s2.25 2 3.75.75Zm0 0c1.5-2.25 3.75-2.25 3.75-.75s-2.25 2-3.75.75Zm-.75 1.75l-.5 2.25m2-2.25l.5 2.25");
}

</style>
