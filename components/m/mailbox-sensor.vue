<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bs259tbbz"/><path class="k0-4f4ccs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mailbox-sensor" /></template>
<style>
.bs259tbbz {
  d: path("M5.125 7h6.75A2.625 2.625 0 0 1 14.5 9.625v4.75A2.625 2.625 0 0 1 11.875 17h-6.75A2.625 2.625 0 0 1 2.5 14.375v-4.75A2.625 2.625 0 0 1 5.125 7m12.125 3.25a2.5 2.5 0 0 1 0 3.5M19.75 8a5 5 0 0 1 0 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0-4f4ccs {
  d: path("m2.5 8.5l6 4l6-4");
}

</style>
