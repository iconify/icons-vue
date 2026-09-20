<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ste6xgm2r"/><path class="f_ocwm2xq"/><path class="fkf_gcbra"/><path class="ugvz7ebru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spice-outline-regular" /></template>
<style>
.f_ocwm2xq {
  d: path("M10 10V6h4v4");
}

.fkf_gcbra {
  d: path("M10 15h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ste6xgm2r {
  d: path("M7 10v11h10V10Z");
}

.ugvz7ebru {
  d: path("M10 18h4");
}

</style>
