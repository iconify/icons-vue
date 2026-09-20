<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q5qu68bdd"/><path class="nm_8gfnlk"/><path class="v-6jjcb6s"/><path class="vg-8fjbxt"/><path class="fnwx1d-uu"/><path class="z1-oixbqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:night-stars-duotone-regular" /></template>
<style>
.fnwx1d-uu {
  d: path("m17 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

.nm_8gfnlk {
  fill: currentColor;
  d: path("m17 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q5qu68bdd {
  fill: currentColor;
  d: path("M8 3.5 11.5 7 8 10.5 4.5 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v-6jjcb6s {
  fill: currentColor;
  d: path("m11 14 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vg-8fjbxt {
  d: path("M8 3.5 11.5 7 8 10.5 4.5 7Z");
}

.z1-oixbqj {
  d: path("m11 14 3 3 -3 3 -3 -3Z");
}

</style>
