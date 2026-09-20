<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iczafxbjt"/><path class="ys95wsbzg"/><path class="i0lroi0ex"/><path class="h2-2dgnfu"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reflect-duotone-regular" /></template>
<style>
.h2-2dgnfu {
  d: path("M12 3v18");
}

.hzsvawc8s {
  d: path("m8 8 -4 4 4 4");
}

.i0lroi0ex {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iczafxbjt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u8aszkb6i {
  d: path("m16 8 4 4 -4 4");
}

.ys95wsbzg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
