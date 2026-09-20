<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="kpspt_bpo"/><path class="p8yct170k"/><path class="bg_wpbcgo"/><path class="lx30vib3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:revision-outline-regular" /></template>
<style>
.bg_wpbcgo {
  d: path("M11 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.lx30vib3e {
  d: path("m18 18 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8yct170k {
  d: path("M7 12h6");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
