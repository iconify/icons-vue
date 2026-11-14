<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evel81brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:storm-track" /></template>
<style>
.evel81brg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 10.5h7a2.75 2.75 0 0 0 .25-5.5a4.25 4.25 0 0 0-8 1a2.5 2.5 0 0 0 .75 4.5m5 2.75l-2.25 3.25H16l-2.25 3.75m-2.986-.402a10 10 0 0 1-2.804-.938m-2.28-1.596A10 10 0 0 1 3.84 15m-1.043-2.581A10 10 0 0 1 2.5 10");
}

</style>
