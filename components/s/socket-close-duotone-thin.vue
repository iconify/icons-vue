<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2epwum2e"/><path class="pnat86b0b"/><path class="qhea8zb8b"/><path class="l1y6mk20t"/><path class="uk7acdcay"/><path class="b4de0eyhw"/><path class="lxtc-wp5b"/><path class="s-cqkabbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:socket-close-duotone-thin" /></template>
<style>
.b4de0eyhw {
  d: path("M16 4h4v16h-4");
}

.h2epwum2e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4H4v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1y6mk20t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 10 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lxtc-wp5b {
  d: path("m10 10 4 4");
}

.pnat86b0b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qhea8zb8b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s-cqkabbd {
  d: path("m14 10 -4 4");
}

.uk7acdcay {
  d: path("M8 4H4v16h4");
}

</style>
