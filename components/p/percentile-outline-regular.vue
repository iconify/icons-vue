<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f1psbbcsw"/><path class="kdl_ri28b"/><path class="lkivjibuo"/><path class="yzvng5w1c"/><path class="e-0451fwt"/><path class="c7dgfu7wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:percentile-outline-regular" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.e-0451fwt {
  d: path("M20 16v4");
}

.f1psbbcsw {
  d: path("M4 15v5");
}

.kdl_ri28b {
  d: path("M8 11v9");
}

.lkivjibuo {
  d: path("M12 13v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yzvng5w1c {
  d: path("M16 7v13");
}

</style>
