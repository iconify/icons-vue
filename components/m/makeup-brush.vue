<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0yvxobrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:makeup-brush" /></template>
<style>
.s0yvxobrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 20l6.36-6.36m-.71-1.41l2.13-2.13q.35-.35.7 0l1.42 1.42q.35.35 0 .7l-2.13 2.13q-.35.35-.7 0l-1.42-1.42q-.35-.35 0-.7m2.83-3.68l.19-.61q.35-1.2 1.41-1.86l.7-.45q1.06-.66 2.26-.32l.08.03q1.2.34 1.54 1.54l.03.08q.34 1.2-.32 2.26l-.45.7q-.66 1.06-1.86 1.41l-.61.19q-1.2.35-2.08-.53l-.36-.36q-.88-.88-.53-2.08");
}

</style>
