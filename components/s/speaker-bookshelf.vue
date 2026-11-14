<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c30j0pdqw"/><path class="ik67nwb5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:speaker-bookshelf" /></template>
<style>
.c30j0pdqw {
  d: path("M7.125 3h9.75A2.625 2.625 0 0 1 19.5 5.625v11.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 16.875V5.625A2.625 2.625 0 0 1 7.125 3M6.5 19.5V21m11-1.5V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik67nwb5z {
  d: path("M8.25 13a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M12 13h.01M12 6.75h.01");
}

</style>
