<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gmjhnix_r"/><path class="dvxrqlb-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sensory-friendly" /></template>
<style>
.dvxrqlb-w {
  d: path("M5 14za2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V16a2 2 0 0 1 2-2m14 0za2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V16a2 2 0 0 1 2-2m-7 4.5S9.75 17 9.75 15.25c0-1 .75-1.75 1.5-1.75c.25 0 .5.25.75.5c.25-.25.5-.5.75-.5c.75 0 1.5.75 1.5 1.75C14.25 17 12 18.5 12 18.5");
}

.gmjhnix_r {
  d: path("M4.5 15v-3a7.5 7.5 0 0 1 15 0v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
