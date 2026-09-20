<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hadc61b6e"/><path class="gxazl9btk"/><path class="x5i0m055t"/><path class="emvotkb4z"/><path class="nnfdo4bja"/><path class="j2hnp9b4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:percent-duotone-regular" /></template>
<style>
.emvotkb4z {
  d: path("M4 20 20 4");
}

.gxazl9btk {
  fill: currentColor;
  d: path("M15 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hadc61b6e {
  fill: currentColor;
  d: path("M5 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j2hnp9b4t {
  d: path("M15 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nnfdo4bja {
  d: path("M5 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x5i0m055t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20 20 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
