<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wp-gahbef"/><path class="qr38rxb4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:satellite-view-sharp" /></template>
<style>
.qr38rxb4x {
  d: path("M2.75 17.75c3.5 0 5-1.25 6.25-3s2.5-2.25 5.75-2.25m2.85-6.9l.8.8l.35.35l-.35.35l-.8.8l-.35.35l-.35-.35l-.8-.8l-.35-.35l.35-.35l.8-.8l.35-.35zm-4.24-.62l2.12-2.12m3.54 7.78l2.12-2.12");
}

.wp-gahbef {
  d: path("M2.75 9.25h12v12h-12z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
