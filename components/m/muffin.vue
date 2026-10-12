<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rx0ylacln"/><path class="ttfah7bxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:muffin" /></template>
<style>
.rx0ylacln {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a9 7.5 0 0 1 18 0a1.25 1.25 0 0 1-1.25 1.25H4.25A1.25 1.25 0 0 1 3 12m3.5 1.25h11l-1 6.25a1.25 1.25 0 0 1-1.25 1h-6.5a1.25 1.25 0 0 1-1.25-1Zm3.75 0l.3 7.25m3.2-7.25l-.3 7.25");
}

.ttfah7bxs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10.25h.01m3.74-2.5h.01m3.99 1.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
