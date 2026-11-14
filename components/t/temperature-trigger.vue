<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1blub1xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temperature-trigger" /></template>
<style>
.i1blub1xh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 13.75V5.5a2.75 2.75 0 0 1 5.5 0v8.25a4.5 4.5 0 1 1-5.5 0Zm2.75 3.5V11m11.75 2.75l-3 4h3.25l-2.75 3.75");
}

</style>
