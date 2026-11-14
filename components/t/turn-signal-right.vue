<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbz6k5bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:turn-signal-right" /></template>
<style>
.cbz6k5bge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.263 10.763l-4.349-4.349A.828.828 0 0 0 14.5 7v.25A1.75 1.75 0 0 1 12.75 9h-8.5a1.75 1.75 0 0 0-1.75 1.75v2.5A1.75 1.75 0 0 0 4.25 15h8.5a1.75 1.75 0 0 1 1.75 1.75V17a.828.828 0 0 0 1.414.586l4.349-4.349a1.75 1.75 0 0 0 0-2.474");
}

</style>
