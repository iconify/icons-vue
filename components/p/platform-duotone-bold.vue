<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="trirghiqk"/><path class="f95tsn8zu"/><path class="grt7vrw-d"/><path class="mqtixbwqo"/><path class="a9nj5hbth"/><path class="ils7yp4cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:platform-duotone-bold" /></template>
<style>
.a9nj5hbth {
  d: path("M4 11h16");
}

.f95tsn8zu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.grt7vrw-d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.trirghiqk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
