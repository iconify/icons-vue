<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7c_b1bsn"/><path class="rc9x_d4xl"/><path class="a218-cpca"/><path class="x97gz5ilw"/><path class="jxjonebqo"/><path class="mk7-jac6n"/><path class="bzffde1kd"/><path class="fsi7fbbnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parking-ticket-duotone-regular" /></template>
<style>
.a218-cpca {
  d: path("M4 5h16a2 2 0 0 1 2 2v3a2 2 0 0 0 0 4v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2v-3a2 2 0 0 0 0 -4V7a2 2 0 0 1 2 -2");
}

.bzffde1kd {
  d: path("M13.5 12h5");
}

.fsi7fbbnr {
  d: path("M13.5 15h5");
}

.jxjonebqo {
  d: path("M8.5 9v3");
}

.mk7-jac6n {
  d: path("M13.5 9h5");
}

.n7c_b1bsn {
  fill: currentColor;
  d: path("M4 5h16a2 2 0 0 1 2 2v3a2 2 0 0 0 0 4v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2v-3a2 2 0 0 0 0 -4V7a2 2 0 0 1 2 -2");
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

.rc9x_d4xl {
  fill: currentColor;
  d: path("M5.5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x97gz5ilw {
  d: path("M5.5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
