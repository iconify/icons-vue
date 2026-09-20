<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vra1stbnu"/><path class="i6clenrss"/><path class="vqy-3paam"/><path class="lf2ilxqms"/><path class="hc7fbd-jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tent-duotone-thin" /></template>
<style>
.hc7fbd-jo {
  d: path("M4 19h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6clenrss {
  d: path("M2 16 12 6l10 10Z");
}

.lf2ilxqms {
  d: path("m12 11 5 5");
}

.vqy-3paam {
  d: path("m12 11 -5 5");
}

.vra1stbnu {
  fill: currentColor;
  d: path("M2 16 12 6l10 10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
