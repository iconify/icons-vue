<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pku6p5b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:naloxone" /></template>
<style>
.pku6p5b-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12za3 3 0 0 1 3 3v3.5a3 3 0 0 1-3 3a3 3 0 0 1-3-3V15a3 3 0 0 1 3-3m-5-2h10a1 1 0 0 1 1 1a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1a1 1 0 0 1 1-1m3.75 0l.5-7c.1-.75 1.4-.75 1.5 0l.5 7m-2.75 6h3");
}

</style>
