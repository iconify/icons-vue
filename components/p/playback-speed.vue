<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rc64qxb9w"/><path class="qo5oz3b7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:playback-speed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qo5oz3b7v {
  d: path("M12.375 16.75za1.45 1.45 0 0 1 0 2.5a1.41 1.41 0 0 1-2.125-1.215v-.07a1.41 1.41 0 0 1 2.125-1.215");
}

.rc64qxb9w {
  d: path("M4.25 17a9 9 0 1 1 15.5 0M12 12.5l4.25-4.25");
}

</style>
