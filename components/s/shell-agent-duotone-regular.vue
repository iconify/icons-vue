<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v7doqbcbe"/><path class="tmkyhwb0s"/><path class="nhtvrskdg"/><path class="l18c8xbrk"/><path class="m4mj7rdxr"/><path class="o96t7tbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shell-agent-duotone-regular" /></template>
<style>
.l18c8xbrk {
  d: path("M8.69 4.37a4 4 0 1 1 -3.38 0");
}

.m4mj7rdxr {
  d: path("m13 12 3.5 3.5L13 19");
}

.nhtvrskdg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 19h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o96t7tbzh {
  d: path("M18.5 19h3");
}

.tmkyhwb0s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 12 3.5 3.5L13 19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v7doqbcbe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 4.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
