<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jn4ih6bid"/><path class="ujw9c-ben"/><path class="c8p2edctq"/><path class="kzxwn_jgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rock-duotone-regular" /></template>
<style>
.c8p2edctq {
  d: path("m9 6 6 6h6");
}

.jn4ih6bid {
  fill: currentColor;
  d: path("m3 12 6 -6h6l6 6 -6 6H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kzxwn_jgc {
  d: path("M15 12v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ujw9c-ben {
  d: path("m3 12 6 -6h6l6 6 -6 6H9Z");
}

</style>
