<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g46yh4b7l"/><path class="s0f7xdhys"/><path class="j330vxbun"/><path class="ucd8o6bjf"/><path class="l3q0873tf"/><path class="fd-_w9lgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:partly-cloudy-duotone-bold" /></template>
<style>
.fd-_w9lgw {
  d: path("M8 21a4 4 0 0 1 2 -7.5 5 5 0 0 1 9 -1 4.5 4.5 0 0 1 3 8.5Z");
}

.g46yh4b7l {
  fill: currentColor;
  d: path("M4 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j330vxbun {
  d: path("M4 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.l3q0873tf {
  d: path("M13.5 2.5 11 5");
}

.s0f7xdhys {
  fill: currentColor;
  d: path("M8 21a4 4 0 0 1 2 -7.5 5 5 0 0 1 9 -1 4.5 4.5 0 0 1 3 8.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ucd8o6bjf {
  d: path("M2.5 2.5 5 5");
}

</style>
