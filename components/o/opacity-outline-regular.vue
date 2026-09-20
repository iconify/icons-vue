<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vyks9vbfn"/><path class="emo-jf0pj"/><path class="aqrpc1aqy"/><path class="a_lj6jt5i"/><path class="a-9s6wb0y"/><path class="l23it1b0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:opacity-outline-regular" /></template>
<style>
.a_lj6jt5i {
  d: path("M9 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.a-9s6wb0y {
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.aqrpc1aqy {
  d: path("M12 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.emo-jf0pj {
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.l23it1b0d {
  d: path("M6 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
