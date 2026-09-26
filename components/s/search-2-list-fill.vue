<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="he2zh4bgk"/><path class="rimuh7bpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-list-fill" /></template>
<style>
.he2zh4bgk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 11C20 15.9706 15.9706 20 11 20C6.0294 20 2 15.9706 2 11C2 6.0294 6.0294 2 11 2C15.9706 2 20 6.0294 20 11ZM8.8 10L11.2 10C11.7523 10 12.2 9.5523 12.2 9C12.2 8.4477 11.7523 8 11.2 8L8.8 8C8.2477 8 7.8 8.4477 7.8 9C7.8 9.5523 8.2477 10 8.8 10ZM8.8 14L13.2 14C13.7523 14 14.2 13.5523 14.2 13C14.2 12.4477 13.7523 12 13.2 12L8.8 12C8.2477 12 7.8 12.4477 7.8 13C7.8 13.5523 8.2477 14 8.8 14Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rimuh7bpm {
  d: path("M17 17L21 21");
}

</style>
