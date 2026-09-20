<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="tbmc7jbly"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="jtt8g10_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:remove-checkpoint-duotone-thin" /></template>
<style>
.bnrf8ghpe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtt8g10_o {
  d: path("M9 10h6");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.tbmc7jbly {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vpuel0dtu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
