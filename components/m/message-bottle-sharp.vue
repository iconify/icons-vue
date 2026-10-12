<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f9dbj628s"/><path class="bdll9pvms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:message-bottle-sharp" /></template>
<style>
.bdll9pvms {
  d: path("m8.11 14.47l3.54-3.53l.35-.35l.35.35l.71.71l.35.35l-.35.35l-3.53 3.54l-.36.35l-.35-.35l-.71-.71l-.35-.35z");
}

.f9dbj628s {
  d: path("m4.4 14.65l6.54-6.54l.71-.71l.99-.05l1.01-.06l1-.06l.62-.62l.62-.62l.71.71l.7.7l.71.71l-.62.62l-.62.62l-.06 1l-.06 1.01l-.05.99l-.71.71l-6.54 6.54l-.71.71l-.71-.71l-3.53-3.53l-.71-.71zM18.01 3.87l.71-.71l.35-.35l.35.35l1.42 1.42l.35.35l-.35.35l-.71.71l-.35.35l-.36-.35l-1.41-1.41l-.35-.36z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
