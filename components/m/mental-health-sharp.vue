<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m6k8k4h8w"/><path class="q9prowbmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mental-health-sharp" /></template>
<style>
.m6k8k4h8w {
  d: path("M15.75 21.25v-3H19v-4l1.5-.5l.865-.346l-.565-.754L19 10c-.25-4.25-3.25-7.25-7.5-7.25C7 2.75 3.75 6 3.75 10.5c0 2.6 1.1 4.5 3 6v4.75Z");
}

.q9prowbmg {
  d: path("M11.25 14.75c-.4 0-3.75-2-3.75-4.4a2 2 0 0 1 3.75-1a2 2 0 0 1 3.75 1c0 2.4-3.35 4.4-3.75 4.4Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
