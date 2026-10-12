<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tjmutzypq"/><path class="px3s8mbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tip-jar" /></template>
<style>
.px3s8mbgg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7.25H7.75a1 1 0 0 0-1 1v2.25m6.75-3.25h2.75a1 1 0 0 1 1 1v2.25m-10.5 0h10.5V12c0 1.5 2.75 1.5 2.75 3.75v3.5a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-3.5C4 13.5 6.75 13.5 6.75 12Z");
}

.tjmutzypq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
