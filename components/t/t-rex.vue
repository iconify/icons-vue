<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc8gvgsbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:t-rex" /></template>
<style>
.kc8gvgsbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5V11c0-5 2.5-7.5 7-7.5h7a2 2 0 0 1 2 2V8L19 9.75L17.5 8L16 9.75L14.5 8h-3l5.5 7.5V17h-5c-1.25 0-2 1-2 2.25v2.25Zm5.5-2l3 1m-4.5-13h.01");
}

</style>
