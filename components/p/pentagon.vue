<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="siaaoqf6v"/><path class="afk3glbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pentagon" /></template>
<style>
.afk3glbhf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.75h.01");
}

.siaaoqf6v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.62 4.18l6.03 4.38q1.62 1.18 1 3.08l-2.3 7.1q-.62 1.9-2.62 1.9H8.27q-2 0-2.62-1.9l-2.3-7.1q-.62-1.9 1-3.08l6.03-4.38Q12 3 13.62 4.18");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
