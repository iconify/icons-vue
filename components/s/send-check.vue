<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmgh1ebgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:send-check" /></template>
<style>
.tmgh1ebgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.595 6.962l6.114-2.445a1.75 1.75 0 0 1 2.274 2.274l-2.445 6.114A1.255 1.255 0 0 1 9.25 13l-.989-1.978a1.75 1.75 0 0 0-.783-.783L5.5 9.25a1.255 1.255 0 0 1 .095-2.288M8 10.5L15.5 3m-.75 15l2 2L21 15.75");
}

</style>
