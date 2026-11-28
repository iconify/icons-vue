<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="unao03b0n"/><path class="m_-hb1b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-dashed-check-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m_-hb1b0m {
  d: path("M8.7071 9.7071L11 12L15.2929 7.7071");
}

.unao03b0n {
  stroke-opacity: 0.4;
  d: path("M3 8.75L3 3L7 3M9.5 3L14.5 3M17 3L21 3L21 8.75M21 11.25L21 17L17 17M15 17L10 17M8 17L7 17L3 21L3 11.25");
}

</style>
