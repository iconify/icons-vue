<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mt8vg0ztk"/><path class="xl0iq-bka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tomato" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mt8vg0ztk {
  d: path("M12 8.25c-1.25-.75-2.75-1-4-.75c-2.75.5-4.75 3-4.75 6.5c0 4 3.75 7 8.75 7s8.75-3 8.75-7c0-3.5-2-6-4.75-6.5c-1.25-.25-2.75 0-4 .75");
}

.xl0iq-bka {
  d: path("m12.15 3.32l.76 1.66q.15.31.5.35l1.81.22q.35.04.09.28l-1.34 1.24q-.26.24-.19.58l.36 1.79q.06.34-.24.17l-1.59-.89q-.31-.17-.62 0l-1.59.89q-.3.17-.24-.17l.36-1.79q.07-.34-.19-.58L8.69 5.83q-.26-.24.09-.28l1.81-.22q.35-.04.5-.35l.76-1.66q.15-.32.3 0");
}

</style>
