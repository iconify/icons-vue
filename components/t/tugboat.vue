<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tcd8adb7t"/><path class="nlo5y8dep"/><path class="wynnj3b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tugboat" /></template>
<style>
.nlo5y8dep {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13.25H16q1 0 1.35-.94l.05-.12q.35-.94 1.35-.94h1.5q1 0 .77.97l-1.29 5.56q-.23.97-1.23.97H6q-1 0-1.38-.93l-1.49-3.64q-.38-.93.62-.93");
}

.tcd8adb7t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 12.25v-2q0-1 1-1h.75q1 0 1-1v-2q0-1 1-1h3q1 0 1 1v6q0 1-1 1H6.75q-1 0-1-1m4.75-4.5h1m4.75 5.5v-7m-1.5 2h3");
}

.wynnj3b6j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 16h.01m3.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
