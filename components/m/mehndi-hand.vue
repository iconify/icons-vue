<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="s6c_q0brx"/><path class="n2039fbrt"/><path class="ua92hsbdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mehndi-hand" /></template>
<style>
.n2039fbrt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.44 13.71l.27.7q.19.46.68.39l.75-.1q.49-.07.18.32l-.46.59q-.31.39 0 .78l.46.59q.31.4-.18.32l-.75-.1q-.49-.07-.68.39l-.27.7q-.19.46-.38 0l-.27-.7q-.19-.46-.68-.39l-.75.1q-.49.08-.18-.32l.46-.59q.31-.39 0-.78l-.46-.59q-.31-.39.18-.32l.75.1q.49.07.68-.39l.27-.7q.19-.46.38 0");
}

.s6c_q0brx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 14.5V8a1.25 1.25 0 0 1 2.5 0V4.75a1.25 1.25 0 0 1 2.5 0v-.5a1.25 1.25 0 0 1 2.5 0v1a1.25 1.25 0 0 1 2.5 0v7.25l1.6-1.6a1.4 1.4 0 0 1 2 2l-3.6 4.35a5.5 5.5 0 0 1-3.75 4h-.75a5.5 5.5 0 0 1-5.5-5.5Z");
}

.ua92hsbdx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 9h.01M10 6h.01m2.49-.5h.01m2.49 1h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
