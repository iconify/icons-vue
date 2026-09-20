<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sbvx6wblx"/><path class="mdssbcbdg"/><path class="ugdbidcqi"/><path class="nnwao2bjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:power-duotone-regular" /></template>
<style>
.mdssbcbdg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nnwao2bjn {
  d: path("M12 3v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sbvx6wblx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

</style>
