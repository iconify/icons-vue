<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hr_66lm0x"/><path class="mmg7i3dlb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:review-edit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr_66lm0x {
  d: path("M5 2.5h11a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-6L6.5 18v-3.5H5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2");
}

.mmg7i3dlb {
  d: path("m11 6.125l.15.338a1.5 1.5 0 0 0 1.205.882l.27.03a.491.491 0 0 1 .266.862l-.208.177a1.5 1.5 0 0 0-.488 1.465l.055.246a.483.483 0 0 1-.727.514l-.228-.142a1.5 1.5 0 0 0-1.59 0l-.228.142a.483.483 0 0 1-.727-.514l.055-.246a1.5 1.5 0 0 0-.488-1.465l-.208-.177a.491.491 0 0 1 .266-.862l.27-.03a1.5 1.5 0 0 0 1.205-.882l.15-.338a.547.547 0 0 1 1 0m10.25 9.625za1.06 1.06 0 0 1 0 1.5l-4.311 4.311a1.5 1.5 0 0 1-1.06.439h-.129a.75.75 0 0 1-.75-.75v-.129a1.5 1.5 0 0 1 .439-1.06l4.311-4.311a1.06 1.06 0 0 1 1.5 0");
}

</style>
