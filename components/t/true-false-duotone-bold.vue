<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pue18lbrd"/><path class="k-a3mgzwy"/><path class="u5rn05amy"/><path class="dt6t4bcmu"/><path class="v99mbcczu"/><path class="brz3--krt"/><path class="n8z3lbl9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:true-false-duotone-bold" /></template>
<style>
.brz3--krt {
  d: path("m15 14 4 4");
}

.dt6t4bcmu {
  d: path("m5 8 2 2 4 -4");
}

.k-a3mgzwy {
  fill: currentColor;
  d: path("M13 12h8v8h-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n8z3lbl9h {
  d: path("m19 14 -4 4");
}

.pue18lbrd {
  fill: currentColor;
  d: path("M3 4h8v8H3Z");
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

.u5rn05amy {
  d: path("M3 4h8v8H3Z");
}

.v99mbcczu {
  d: path("M13 12h8v8h-8Z");
}

</style>
