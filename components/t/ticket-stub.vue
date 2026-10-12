<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qbjeadr5m"/><path class="bx96upgpl"/><path class="sb2uf-bwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ticket-stub" /></template>
<style>
.bx96upgpl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.15 6.62l.49 1.17q.15.37.55.4l1.26.1q.4.03.1.29l-.96.83q-.31.26-.21.65l.29 1.23q.09.39-.25.18l-1.08-.66q-.34-.21-.68 0l-1.08.66q-.34.21-.25-.18l.29-1.23q.1-.39-.21-.65l-.96-.83q-.3-.26.1-.29l1.26-.1q.4-.03.55-.4l.49-1.17q.15-.37.3 0");
}

.qbjeadr5m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.25a1.5 1.5 0 0 1 1.5-1.5h11a1.5 1.5 0 0 1 1.5 1.5v14L17.25 18l-1.75 1.25L13.75 18L12 19.25L10.25 18L8.5 19.25L6.75 18L5 19.25Z");
}

.sb2uf-bwr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 14.25h.01m2.24 0h.01m2.49 0h.01m2.49 0h.01m2.24 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
