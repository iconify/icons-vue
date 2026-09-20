<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsxmkkb6q"/><path class="mbt4yzbhr"/><path class="uv3i8hbxr"/><path class="w2l9ffbxv"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="oh3t_sdfd"/><path class="b4nrz0b6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-close-duotone-regular" /></template>
<style>
.b4nrz0b6r {
  d: path("m20.5 10.5 -5 5");
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oh3t_sdfd {
  d: path("m15.5 10.5 5 5");
}

.oscmqi7_r {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

.rsxmkkb6q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uv3i8hbxr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15.5 10.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w2l9ffbxv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20.5 10.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
