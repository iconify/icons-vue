<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n81kl2bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:message-bubble-pair" /></template>
<style>
.n81kl2bkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3h7A2.5 2.5 0 0 1 15 5.5v3a2.5 2.5 0 0 1-2.5 2.5H6l-3 2V5.5A2.5 2.5 0 0 1 5.5 3m6 10.75h7a2.5 2.5 0 0 1 2.5 2.5V21l-3-2h-6.5A2.5 2.5 0 0 1 9 16.5v-.25a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
