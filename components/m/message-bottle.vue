<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpnelhb9i"/><path class="wv7h0uohb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:message-bottle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpnelhb9i {
  d: path("m4.4 14.65l6.54-6.54q.71-.71 1.7-.76l1.01-.06q1-.06 1.62-.68t1.33.09l.7.7q.71.71.09 1.33t-.68 1.62l-.06 1.01q-.05.99-.76 1.7L9.35 19.6q-.71.71-1.42 0L4.4 16.07q-.71-.71 0-1.42M18.01 3.87l.71-.71q.35-.35.7 0l1.42 1.42q.35.35 0 .7l-.71.71q-.35.35-.71 0l-1.41-1.41q-.35-.36 0-.71");
}

.wv7h0uohb {
  d: path("m8.11 14.47l3.54-3.53q.35-.35.7 0l.71.71q.35.35 0 .7l-3.53 3.54q-.36.35-.71 0l-.71-.71q-.35-.35 0-.71");
}

</style>
