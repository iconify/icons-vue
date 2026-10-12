<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hqnx7t4cz"/><path class="r8j-njbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinata-stick" /></template>
<style>
.hqnx7t4cz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.64 3.32l1.04 2.29q.14.32.49.36l2.5.27q.35.04.09.28L18.9 8.21q-.26.24-.19.58l.51 2.46q.07.34-.23.17l-2.19-1.25q-.3-.17-.6 0l-2.19 1.25q-.3.17-.23-.17l.51-2.46q.07-.34-.19-.58l-1.86-1.69q-.26-.24.09-.28l2.5-.27q.35-.04.49-.36l1.04-2.29q.14-.32.28 0M3.33 20.33l.34.34q.71.71 1.42 0l6.33-6.33q.71-.71 0-1.42l-.34-.34q-.71-.71-1.42 0l-6.33 6.33q-.71.71 0 1.42M5.6 16.6l1.8 1.8m1.2-4.8l1.8 1.8");
}

.r8j-njbfo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 15.5h.01m3.24-.75h.01m-1.26 3.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
