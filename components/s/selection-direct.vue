<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbz-8qhlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:selection-direct" /></template>
<style>
.mbz-8qhlp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.052 5.526l5.113 2.557A1.035 1.035 0 0 1 13 10l-1.646.494a1.75 1.75 0 0 0-1.149 1.098l-.58 1.658a.977.977 0 0 1-1.833.03L5.638 7.724a1.75 1.75 0 0 1 2.414-2.198M17 15.5h2a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
