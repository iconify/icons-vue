<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="rlv_-eb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:military-id" /></template>
<style>
.hneliqdkn {
  d: path("M2.5 4h19v16h-19Z");
}

.rlv_-eb8e {
  d: path("m7 6.25l.647 1.61l1.731.117L8.046 9.09l.423 1.683L7 9.85l-1.469.923l.423-1.683l-1.332-1.113l1.731-.117ZM5 15.5h4.5m3.5-4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM11.25 20c0-3 2-4 4.25-4s4.25 1 4.25 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
