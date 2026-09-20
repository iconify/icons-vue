<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h78mtnbkg"/><path class="icdzo3brn"/><path class="sux3x4evg"/><path class="md3qg6xkk"/><path class="pty_wsbvs"/><path class="wvee1b7zr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-action-duotone-regular" /></template>
<style>
.h78mtnbkg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.icdzo3brn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.md3qg6xkk {
  d: path("M4 6v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.sux3x4evg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wvee1b7zr {
  d: path("M8 15h12");
}

</style>
