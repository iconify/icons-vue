<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="uai51xb0f"/><path class="jte4c6-2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:porcupine" /></template>
<style>
.jte4c6-2i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 14.75h.01");
}

.uai51xb0f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 17.5c-1 0-1.75-.75-1.75-1.75s.9-2.15 2.15-2.45C6.9 11.5 9.5 10.75 12 10.75c4.25 0 7.5 2.75 7.5 6.75Zm3.75-6l2.5-7m1 6.25l3.5-7.25m-.25 7.9l4.5-5.9m-1.85 7.9l3.35-3.4M7 17.5v2m8.5-2v2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
