<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_rtjybvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pilsner-glass" /></template>
<style>
.d_rtjybvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.83 2.5h6.34a1.5 1.5 0 0 1 1.471 1.794l-2.55 12.749a1.5 1.5 0 0 0 .093.885l.566 1.322A1.255 1.255 0 0 1 13.596 21h-3.192a1.255 1.255 0 0 1-1.154-1.75l.566-1.322a1.5 1.5 0 0 0 .093-.885L7.359 4.294A1.5 1.5 0 0 1 8.83 2.5");
}

</style>
