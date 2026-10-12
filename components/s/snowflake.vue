<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kw36iwr5n"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snowflake" /></template>
<style>
.kw36iwr5n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.75v-6m0 12.5v6m2.81-10.87l5.2-3m-5.2 6.25l5.2 3m-10.82-3l-5.2 3m5.2-6.25l-5.2-3m9.78-2.15L12 7l-1.77-1.77m8.51 4.92l-2.41-.65l.65-2.41m0 9.82l-.65-2.41l2.41-.65m-8.51 4.92L12 17l1.77 1.77m-8.51-4.92l2.41.65l-.65 2.41m0-9.82l.65 2.41l-2.41.65");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
