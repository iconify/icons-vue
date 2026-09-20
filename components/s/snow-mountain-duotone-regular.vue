<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o3pzlzlbb"/><path class="u5mdljjhy"/><path class="kakiz1beo"/><path class="jszbb1ext"/><path class="ujgggmb5i"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:snow-mountain-duotone-regular" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.jszbb1ext {
  d: path("m2 18 8 -8 4 4 6 -6 2 2");
}

.kakiz1beo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o3pzlzlbb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m2 18 8 -8 4 4 6 -6 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u5mdljjhy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 13 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ujgggmb5i {
  d: path("m7 13 3 -3 3 3");
}

</style>
