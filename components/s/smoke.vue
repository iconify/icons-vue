<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="k8yqfzddt"/><path class="dm6-i9zis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smoke" /></template>
<style>
.dm6-i9zis {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 4.5h.01M3 7.5h.01m13.24 0h.01");
}

.k8yqfzddt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V14a1 1 0 0 1 1-1h3v-2a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1v4h2.5v-3a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1v9.25Zm0-16.75h6.5m3.25 0h8.75m-16 3h9.5m3 0h3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
