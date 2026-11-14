<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnl2hsbik"/><path class="fw2jq4b8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moodboard-pin" /></template>
<style>
.bnl2hsbik {
  d: path("M7.125 7h9.75A2.625 2.625 0 0 1 19.5 9.625v8.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 17.875v-8.25A2.625 2.625 0 0 1 7.125 7M9.75 4.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 6.75V9.5");
}

.fw2jq4b8n {
  d: path("m7.5 17.5l3-4L13 16l1.5-1.5l2 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
