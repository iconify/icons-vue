<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rkhcfx2ju"/><path class="x2s10abgt"/><path class="festcnvxk"/><path class="bx3fv3b8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:optimiser-duotone-thin" /></template>
<style>
.bx3fv3b8c {
  d: path("M12 13v4");
}

.festcnvxk {
  d: path("m3 7 6 6h6l6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rkhcfx2ju {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 7 6 6h6l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x2s10abgt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
