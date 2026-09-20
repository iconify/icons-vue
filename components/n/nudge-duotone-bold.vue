<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jxwl6acrk"/><path class="m9suxjxea"/><path class="rycut8jxl"/><path class="v-m1aobza"/><path class="e0ead5bmw"/><path class="pf-zwj5ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nudge-duotone-bold" /></template>
<style>
.e0ead5bmw {
  d: path("M3 12h3");
}

.jxwl6acrk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.32 7a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m9suxjxea {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pf-zwj5ei {
  d: path("m6 10 2 2 -2 2");
}

.rycut8jxl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v-m1aobza {
  d: path("M16.32 7a5.5 5.5 0 1 1 -4.64 0");
}

</style>
