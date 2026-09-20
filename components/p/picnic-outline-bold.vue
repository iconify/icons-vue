<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="djqc4ackk"/><path class="yaum7gn-a"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:picnic-outline-bold" /></template>
<style>
.djqc4ackk {
  d: path("M5 9v9h14V9Z");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yaum7gn-a {
  d: path("M7 9a5 5 0 0 1 10 0");
}

</style>
