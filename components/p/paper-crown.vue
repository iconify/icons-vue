<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pjuyuub6e"/><path class="rkkkpsmns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-crown" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pjuyuub6e {
  d: path("m3.7 14.33l-.24-4.94q-.05-.9.54-.22l1.05 1.2q.59.68.84-.19l1.04-3.66q.25-.87.68-.08l1.72 3.21q.43.79.64-.09l1.12-4.65q.21-.88.57-.06l1.92 4.4q.36.82.69-.02l1.11-2.74q.33-.84.77-.05l1.51 2.73q.44.79.94.04l.77-1.16q.5-.75.61.14l.6 4.67q.11.89-.79.97L4.65 15.15q-.9.08-.95-.82");
}

.rkkkpsmns {
  d: path("m4.75 15.14l14.94-1.3q1-.09 1.09.91l.21 2.48q.09 1-.91 1.09l-14.94 1.3q-1 .09-1.09-.91l-.21-2.48q-.09-1 .91-1.09M16.7 14.1l.39 4.48");
}

</style>
