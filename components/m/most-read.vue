<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwh4phsgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:most-read" /></template>
<style>
.nwh4phsgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M3 9.5h18M3 15h7m8-.75l.106.264a1.75 1.75 0 0 0 1.45 1.092l.213.021a.586.586 0 0 1 .356.998l-.157.157a1.75 1.75 0 0 0-.451 1.698l.108.395a.573.573 0 0 1-.847.642l-.378-.227a1.75 1.75 0 0 0-1.8 0l-.378.227a.573.573 0 0 1-.847-.642l.108-.395a1.75 1.75 0 0 0-.451-1.698l-.157-.157a.586.586 0 0 1 .356-.998l.213-.021a1.75 1.75 0 0 0 1.45-1.092L17 14.25a.539.539 0 0 1 1 0");
}

</style>
