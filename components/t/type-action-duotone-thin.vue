<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ra6o68b-z"/><path class="mzjqjtrpb"/><path class="c7p9d-b6q"/><path class="md3qg6xkk"/><path class="pty_wsbvs"/><path class="wvee1b7zr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-action-duotone-thin" /></template>
<style>
.c7p9d-b6q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.md3qg6xkk {
  d: path("M4 6v12");
}

.mzjqjtrpb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.ra6o68b-z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wvee1b7zr {
  d: path("M8 15h12");
}

</style>
