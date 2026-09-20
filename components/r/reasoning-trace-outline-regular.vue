<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g3lrzsbos"/><path class="uepsd3bvn"/><path class="q83h1dbic"/><path class="m_5u0ccez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reasoning-trace-outline-regular" /></template>
<style>
.g3lrzsbos {
  d: path("M3 5h7");
}

.m_5u0ccez {
  d: path("M15 20h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q83h1dbic {
  d: path("M11 15h7");
}

.uepsd3bvn {
  d: path("M7 10h7");
}

</style>
