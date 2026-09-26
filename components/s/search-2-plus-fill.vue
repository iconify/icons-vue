<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ub68x7b8k"/><path class="rimuh7bpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-plus-fill" /></template>
<style>
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

.ub68x7b8k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 11C20 15.9706 15.9706 20 11 20C6.0294 20 2 15.9706 2 11C2 6.0294 6.0294 2 11 2C15.9706 2 20 6.0294 20 11ZM12 10L14 10C14.5523 10 15 10.4477 15 11C15 11.5523 14.5523 12 14 12L12 12L12 14C12 14.5523 11.5523 15 11 15C10.4477 15 10 14.5523 10 14L10 12L8 12C7.4477 12 7 11.5523 7 11C7 10.4477 7.4477 10 8 10L10 10L10 8C10 7.4477 10.4477 7 11 7C11.5523 7 12 7.4477 12 8L12 10Z");
  stroke: none;
}

</style>
