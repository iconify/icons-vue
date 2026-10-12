<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fynv3k-gj"/><path class="m_apzdbts"/><path class="rw6q1k_hg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sad-react" /></template>
<style>
.fynv3k-gj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35c-.1.6.45 1.1 1 .95Z");
}

.m_apzdbts {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.75h.01m5.49 0h.01");
}

.rw6q1k_hg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 15.25a3.5 3.5 0 0 1 5.5 0m2.5-4.25c.6.9 1 1.5 1 2a1 1 0 0 1-2 0c0-.5.4-1.1 1-2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
