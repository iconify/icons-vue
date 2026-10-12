<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="i_sc52z6z"/><path class="wsz-fhheg"/><path class="e_5d5nbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:message-quote" /></template>
<style>
.e_5d5nbjm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.5c0 1.6-.8 2.75-2.25 3.25M15.5 9.5c0 1.6-.8 2.75-2.25 3.25");
}

.i_sc52z6z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v9a2.5 2.5 0 0 1-2.5 2.5H12.5L8 20.85a.77.77 0 0 1-1.25-.6v-2.5h-1.5a2.5 2.5 0 0 1-2.5-2.5Z");
}

.wsz-fhheg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.5h.01m5.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
