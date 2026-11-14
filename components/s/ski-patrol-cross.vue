<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z2_8lybtw"/><path class="aitnd7-zo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-patrol-cross" /></template>
<style>
.aitnd7-zo {
  d: path("M11.25 6.5h1.5a1.5 1.5 0 0 1 1.5 1.5v.25a1.5 1.5 0 0 0 1.5 1.5H16a1.5 1.5 0 0 1 1.5 1.5v1.5a1.5 1.5 0 0 1-1.5 1.5h-.25a1.5 1.5 0 0 0-1.5 1.5V16a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5v-.25a1.5 1.5 0 0 0-1.5-1.5H8a1.5 1.5 0 0 1-1.5-1.5v-1.5A1.5 1.5 0 0 1 8 9.75h.25a1.5 1.5 0 0 0 1.5-1.5V8a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2_8lybtw {
  d: path("M9.125 3h5.75A6.125 6.125 0 0 1 21 9.125v5.75A6.125 6.125 0 0 1 14.875 21h-5.75A6.125 6.125 0 0 1 3 14.875v-5.75A6.125 6.125 0 0 1 9.125 3");
}

</style>
