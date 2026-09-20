<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="md3qg6xkk"/><path class="pty_wsbvs"/><path class="wvee1b7zr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-action-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.md3qg6xkk {
  d: path("M4 6v12");
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.wvee1b7zr {
  d: path("M8 15h12");
}

</style>
