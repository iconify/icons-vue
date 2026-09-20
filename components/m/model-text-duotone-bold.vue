<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w2ed1xbxm"/><path class="p39ktbcba"/><path class="xrit8bb9e"/><path class="ltxni2ncy"/><path class="vg0qlegui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-text-duotone-bold" /></template>
<style>
.ltxni2ncy {
  d: path("M14 12h7");
}

.p39ktbcba {
  d: path("m7 8 4 4 -4 4 -4 -4Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vg0qlegui {
  d: path("M14 17h7");
}

.w2ed1xbxm {
  fill: currentColor;
  d: path("m7 8 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xrit8bb9e {
  d: path("M14 7h7");
}

</style>
