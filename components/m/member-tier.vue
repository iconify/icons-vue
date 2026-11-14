<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yoftwf7ei"/><path class="y5tshmb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:member-tier" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5tshmb6t {
  d: path("M8.25 13.75L7 21h3l.75-6.25m5-1L17 21h-3l-.75-6.25m-.875-8l.052.138a1.5 1.5 0 0 0 1.238.964l.281.031a.51.51 0 0 1 .304.867l-.168.168a1.5 1.5 0 0 0-.403 1.386l.071.321a.483.483 0 0 1-.727.514l-.228-.142a1.5 1.5 0 0 0-1.59 0l-.228.142a.483.483 0 0 1-.727-.514l.071-.321a1.5 1.5 0 0 0-.403-1.386L9.75 8.75a.51.51 0 0 1 .304-.867l.281-.031a1.5 1.5 0 0 0 1.238-.964l.052-.138a.401.401 0 0 1 .75 0");
}

.yoftwf7ei {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
